---
author: Rowan Brad Quni
email: rowan.quni@qnfo.org
website: http://qnfo.org
ORCID: https://orcid.org/0009-0002-4317-5604
robots: By accessing this content, you agree to https://qnfo.org/LICENSE. Non-commercial use only. Attribution required.
DC.rights: https://qnfo.org/LICENSE. Users are bound by terms upon access.
title: CausalGraph
aliases: [CausalGraph]
created: 2025-04-03T15:02:06Z
modified: 2025-04-03T15:02:42Z
---

```python
# Name: CausalGraph.py
# Purpose: Simulate a causal graph to model instruction propagation.
# Status: Final version with dependency fixes and clear structure.

import numpy as np
import matplotlib.pyplot as plt
import micropip

# Install numpy and matplotlib for Pyodide
await micropip.install('numpy')
await micropip.install('matplotlib')

class Node:
    def __init__(self, id):
        self.id = id
        self.state = None
        self.instructions = []

    def apply_instructions(self):
        """Apply all instructions to the node's state."""
        for instr in self.instructions:
            instr.apply()

class Instruction:
    def __init__(self, source_node, target_node, effect):
        self.source_node = source_node
        self.target_node = target_node
        self.effect = effect  # Function defining the state update

    def apply(self):
        """Update the target node's state based on the source's state."""
        self.target_node.state = self.effect(self.source_node.state)

class CausalGraph:
    def __init__(self, num_nodes):
        self.nodes = [Node(i) for i in range(num_nodes)]
        self.edges = []
        self.time_steps = 0

    def add_edge(self, source_id, target_id, effect):
        """Add an edge with an instruction between nodes."""
        source_node = self.nodes[source_id]
        target_node = self.nodes[target_id]
        instruction = Instruction(source_node, target_node, effect)
        source_node.instructions.append(instruction)
        self.edges.append((source_id, target_id, instruction))

    def simulate(self, steps):
        """Simulate the causal graph over time steps."""
        for _ in range(steps):
            for edge in self.edges:
                edge[2].apply()  # Apply the instruction
            self.time_steps += 1

    def visualize(self):
        """Plot the causal graph's edges over time."""
        fig, ax = plt.subplots(figsize=(10, 5))
        for edge in self.edges:
            source, target, _ = edge
            ax.plot([source, target], [self.time_steps, self.time_steps], 'r--')
        ax.set_xlim(-1, len(self.nodes))
        ax.set_ylim(-1, self.time_steps + 1)
        ax.set_xlabel('Nodes')
        ax.set_ylabel('Time Steps')
        ax.set_title('Causal Graph Simulation')
        plt.show()

# Example Usage
if __name__ == "__main__":
    # Initialize a causal graph with 5 nodes
    cg = CausalGraph(5)

    # Define edges with state-update effects
    cg.add_edge(0, 1, lambda x: x + 1)  # Node 0 increments neighbor
    cg.add_edge(1, 2, lambda x: x * 2)  # Node 1 doubles neighbor's state
    cg.add_edge(2, 3, lambda x: x - 1)  # Node 2 decrements neighbor
    cg.add_edge(3, 4, lambda x: x / 2)  # Node 3 halves neighbor's state

    # Set initial states
    cg.nodes[0].state = 10.0
    cg.nodes[1].state = 5.0
    cg.nodes[2].state = 3.0
    cg.nodes[3].state = 7.0
    cg.nodes[4].state = 2.0

    # Simulate for 10 time steps
    cg.simulate(10)

    # Visualize the causal connections
    cg.visualize()
```