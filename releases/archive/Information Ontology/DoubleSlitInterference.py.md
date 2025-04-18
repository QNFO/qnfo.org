---
author: Rowan Brad Quni
email: rowan.quni@qnfo.org
website: http://qnfo.org
ORCID: https://orcid.org/0009-0002-4317-5604
robots: By accessing this content, you agree to https://qnfo.org/LICENSE. Non-commercial use only. Attribution required.
DC.rights: https://qnfo.org/LICENSE. Users are bound by terms upon access.
created: 2025-04-03T14:51:24Z
modified: 2025-04-03T18:21:24Z
title: DoubleSlitInterference.py
aliases: [DoubleSlitInterference.py, DoubleSlitInterference]
---

```python
# Name: DoubleSlitInterference.py
# Purpose: Model photon interference using entanglement edges (no medium required).
# Status: Toy model with foundational progress.

import numpy as np
import micropip
await micropip.install('numpy')
await micropip.install('matplotlib')

class QubitNode:
    def __init__(self, id):
        self.id = id
        self.state = np.array([1.0, 0.0])  # |0⟩ superposition
        self.edges = []  # Entanglement connections

class CausalGraph:
    def __init__(self, num_nodes):
        self.nodes = [QubitNode(i) for i in range(num_nodes)]
        self.time_steps = 0

    def entangle(self, source_id, target_id):
        # Create Bell state entanglement
        source = self.nodes[source_id]
        target = self.nodes[target_id]
        
        source.state = np.array([1.0, 1.0]) / np.sqrt(2)
        target.state = np.array([1.0, -1.0]) / np.sqrt(2)
        
        source.edges.append(target)
        target.edges.append(source)

    def simulate_double_slit(self):
        # Nodes: 0=left slit, 1=right slit, 2=detector
        self.entangle(0, 2)  # Left slit ↔ detector
        self.entangle(1, 2)  # Right slit ↔ detector
        
        # Measure detector node (2)
        probabilities = np.abs(self.nodes[2].state)**2
        outcome = np.random.choice([0,1], p=probabilities)
        
        return outcome

    def run_experiment(self, trials):
        results = np.zeros(2)
        for _ in range(trials):
            result = self.simulate_double_slit()
            results[result] += 1
        return results

# Run 1000 trials
graph = CausalGraph(3)
counts = graph.run_experiment(1000)
print("Interference pattern:", counts)  # Should show [500, 500] (no zeros) → fails!

# Plot
plt.bar([0,1], counts)
plt.title('Double-Slit Results (Failed)')
plt.xlabel('Detector Position')
plt.ylabel('Counts')
plt.show()
```