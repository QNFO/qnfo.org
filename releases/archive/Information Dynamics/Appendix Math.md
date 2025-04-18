---
robots: By accessing this content, you agree to https://qnfo.org/LICENSE. Non-commercial use only. Attribution required.
DC.rights: https://qnfo.org/LICENSE. Users are bound by terms upon access.
author: Rowan Brad Quni
email: rowan.quni@qnfo.org
website: http://qnfo.org
LinkedIn: https://www.linkedin.com/in/rowan-quni-868006341
ORCID: https://orcid.org/0009-0002-4317-5604
tags: QNFO, AI, ArtificialIntelligence, artificial intelligence, quantum, physics, science, Einstein, QuantumMechanics, quantum mechanics, QuantumComputing, quantum computing, information, InformationTheory, information theory, InformationalUniverse, informational universe, informational universe hypothesis, IUH
created: 2024-11-13T19:54:01Z
modified: 2025-04-05T07:08:17Z
aliases: ["**Appendix: Mathematical Symbols and Formalisms in Information Dynamics**"]
title: Appendix Math
---
# **Appendix: Mathematical Symbols and Formalisms in Information Dynamics**

---

## **1. Fundamental Variables**

**Existence ($X$)**
- **Definition**: A binary predicate indicating whether an entity holds information states ($X = 1$) or not ($X = 0$).
- **Formula**: $X \in \{0, 1\}$, inferred from $\mathbf{I} \neq \mathbf{0}$.
- **Example**:
  - A particle’s wavefunction has $X = 1$. A vacuum with zero quantum fields has $X = 0$.
- **Notation**:
  - Boldface denotes vectors (e.g., $\mathbf{I}$).
  - Scalar values are non-bold (e.g., $X$, $\epsilon$).

---

## **2. Universal Information ($\mathbf{I}$)**

- **Definition**: A **multi-dimensional vector** encoding all possible states of an entity.
- **Formula**:

  $$
  \mathbf{I} \in \mathbb{R}^D \quad \text{(Continuous, non-physical)}  

$
$  

  - $D$: Total number of informational dimensions (e.g., position, spin, energy).
- **Component Example**:
  - Position: $I_{\text{position}} = I_1 \in \mathbb{R}^3$.
  - Spin: $I_{\text{spin}} = I_2 \in \mathbb{R}$.
- **Observation Index**:
  - $\mathbf{I}_k$: The $k$-th observation (vector in $D$-dimensional space).
  - **Example**:

    $$
    \mathbf{I}_5 = \begin{pmatrix} I_{51}, I_{52}, \dots, I_{5D} \end{pmatrix}^T \quad \text{(5th observation with $D$ dimensions)}  
    
$$  

---

## **3. Resolution Parameter ($\epsilon$)**

- **Definition**: A scalar defining the precision of measurement, discretizing $\mathbf{I}$ into observable data.
- **Formula**:

  $$
  \epsilon > 0 \quad \text{(Unit-dependent, e.g., meters, seconds)}  

$
$  

- **Example**:
  - Quantum regime: $\epsilon \sim 10^{-35} \text{ m}$ (Planck scale).
  - Classical regime: $\epsilon \gg 10^{-35} \text{ m}$.
- **Discretization**:

  $$

  \hat{\mathbf{I}} = \text{round}\left( \frac{\mathbf{I}}{\epsilon} \right) \cdot \epsilon \quad \text{(Observed data)}  

$$  

---

## **4. Contrast ($\kappa$)**

- **Definition**: Normalized difference between information states, quantifying distinguishability.
- **Formula**:

  $$

  \kappa(\mathbf{I}_i, \mathbf{I}_j) = \frac{\|\mathbf{I}_i - \mathbf{I}_j\|}{\epsilon} \quad \text{(Euclidean norm)}  

$$  

- **Example**:
  - Two quantum states with $\kappa \geq 1$ are distinguishable at Planck-scale $\epsilon$.
- **Single-axis contrast**:

  $$

  \kappa_d(\mathbf{I}*i, \mathbf{I}*j) = \frac{|I*{id} - I*{jd}|}{\epsilon} \quad \text{(Difference along dimension $d$)}  

$$  

---

## **5. Sequence ($\tau$)**

- **Definition**: An ordered list of information vectors, forming an emergent timeline.
- **Formula**:

  $$

  \tau = \left( \mathbf{I}_1, \mathbf{I}_2, \dots, \mathbf{I}_N \right) \quad \text{(Cardinality: $|\tau| = N$)}  

$$  

- **Time Emergence**:

  $$

  t \propto \frac{|\tau|}{\epsilon} \quad \text{(Time scales with sequence length and resolution)}  

$$  

- **Example**:
  - A particle’s trajectory: $\tau = \left( \mathbf{I}_{\text{position}_1}, \mathbf{I}_{\text{position}_2}, \dots \right)$.

---

## **6. Information Density ($\rho_{\mathbf{I}}$)**

- **Definition**: Concentration of distinguishable states over a region and sequence interval.
- **Formula**:

  $$

  \rho_{\mathbf{I}} = \frac{\text{Count}(\kappa(\mathbf{I}_i, \mathbf{I}_j) \geq 1)}{\epsilon^D \cdot \Delta|\tau|} \quad \text{(Volume: $\epsilon^D$, sequence interval: $\Delta|\tau|$)}  

$$  

- **Example**:
  - High $\rho_{\mathbf{I}}$ in a galaxy’s stars explains gravity without dark matter.

---

## **7. Entropy ($H$)**

- **Definition**: Disorder in information states over a sequence.
- **Discrete Formulation**:

  $$

  H(\tau) = -\sum_{k=1}^{|\tau|} P(\mathbf{I}_k) \log P(\mathbf{I}_k)  

$$  

- **Continuous Formulation**:

  $$

  H_{\text{cont}} = -\int_{\tau} p(\mathbf{I}) \log p(\mathbf{I}) \, d\mathbf{I}  

$$  

- **Example**:
  - A broken egg has higher $H$ due to more positional and thermal state permutations.

---

## **8. Gravity ($G$)**

- **Definition**: Emergent force from information density and sequence dynamics.
- **Formula**:

  $$

  G \propto \rho_{\mathbf{I}} \cdot \kappa_{\text{avg}} \cdot \frac{d|\tau|}{d\epsilon}  

$$  

  - $\kappa_{\text{avg}} = \frac{1}{|\tau|^2} \sum_{i,j} \kappa(\mathbf{I}_i, \mathbf{I}_j)$.
- **Example**:
  - Galactic rotation curves arise from $\rho_{\mathbf{I}} \cdot \kappa_{\text{avg}}$, not dark matter.

---

## **9. Consciousness ($\phi$)**

- **Definition**: Emergent complexity from mimicry, causality, and repetition.
- **Formula**:

  $$

  \phi \propto M \cdot \lambda \cdot \rho  

$$  

  - $M$: Similarity between sequences ($M = \frac{\sum \kappa(\mathbf{I}_i, \mathbf{I}_j)}{|\tau|}$).
  - $\lambda$: Causality ($\lambda = \frac{P(\mathbf{I}_b | \mathbf{I}_a)}{P(\mathbf{I}_b)}$).
  - $\rho$: Repetition fraction ($\rho = \frac{\text{Repeated states}}{|\tau|}$).
- **Example**:
  - Human consciousness requires $\phi > \phi_{\text{threshold}}$ due to neural repetition and mimicry.

---

## **10. Change ($\Delta \mathbf{I}$)**

- **Definition**: Transition between states in $\tau$.
- **Formula**:

  $$

  \Delta \mathbf{I} = \mathbf{I}_{k+1} - \mathbf{I}_k \quad \text{(Difference between consecutive observations)}  

$$  

- **Example**:
  - A photon’s polarization change: $\Delta I_{\text{polarization}}$.

---

## **11. Repetition ($\rho$)**

- **Definition**: Frequency of repeated states in $\tau$.
- **Formula**:

  $$

  \rho = \frac{\sum_{k=1}^{|\tau|} \sum_{j=k+1}^{|\tau|} \delta(\mathbf{I}_k, \mathbf{I}_j)}{|\tau|} \quad \text{(Dirac delta for state equality)}  

$$  

- **Example**:
  - Earth’s daily rotation: $\rho_{\text{rotation}} \approx 1$ (repeats every $24$ hours).

---

## **12. Causality ($\lambda$)**

- **Definition**: Directional dependency between states via conditional probabilities.
- **Formula**:

  $$

  \lambda(\mathbf{I}_a \rightarrow \mathbf{I}_b) = \frac{P(\mathbf{I}_b | \mathbf{I}_a)}{P(\mathbf{I}_b)}  

$$  

- **Example**:
  - A billiard ball’s motion: $\lambda_{\text{collision}}$ predicts post-collision states.

---

## **13. Mimicry ($M$)**

- **Definition**: Similarity between sequences or states.
- **Formula**:

  $$

  M = \frac{\sum_{d=1}^D \sum_{i,j} \kappa_d(\mathbf{I}_i, \mathbf{I}_j)}{D \cdot |\tau|} \quad \text{(Normalized contrast across dimensions)}  

$$  

- **Example**:
  - Quantum entanglement: $M_{\text{entangled}} \geq 1$ at fine $\epsilon$.

---

## **14. Probability ($P$)**

- **Definition**: Probability of an information state occurring in $\tau$.
- **Formula**:

  $$

  P(\mathbf{I}_k) = \frac{\text{Frequency of } \mathbf{I}_k \text{ in } \tau}{|\tau|}  

$$  

- **Example**:
  - A fair coin: $P(I_{\text{heads}}) = P(I_{\text{tails}}) = 0.5$.

---

## **15. Informational Dimensions ($D$ and $d$)**

- **$D$**: Total dimensions (uppercase).
  - **Example**: A particle’s $D = 3$ (position) + $1$ (spin) + $1$ (energy) → $D = 5$.
- **$d$**: Specific dimension index (lowercase).
  - **Example**: $I_{\text{position}} = I_{d=1}$.

---

## **16. Edge Networks**

- **Definition**: Graphs encoding informational correlations ($\kappa \geq 1$).
- **Formula**:

  $$

  G = (V, E) \quad \text{where } V = \{\mathbf{I}_1, \dots, \mathbf{I}_N\}, \quad E = \{\kappa(\mathbf{I}_i, \mathbf{I}_j) \geq 1\}  

$$  

- **Example**:
  - Quantum entanglement forms edges $E$ with $\kappa \geq 1$.

---

# **Notation Conventions**

1. **Vectors**:
   - Boldface ($\mathbf{I}$) denotes vectors.
   - Subscripts: $\mathbf{I}_k$ (observation $k$), $I_{kd}$ (dimension $d$ of observation $k$).

2. **Scalars**:
   - Non-bold symbols ($\epsilon$, $H$, $G$) are scalars.

3. **Indices**:
   - $k$: Observation index (rows in a dataset).
   - $d$: Dimension index (columns in a dataset).

4. **Functions**:
   - $\text{round}(\cdot)$: Discretizes $\mathbf{I}$ into $\hat{\mathbf{I}}$.
   - $\delta(\cdot)$: Dirac delta function for state equality.

---

# **Expressions And Equations**

## **1. Contrast Between States**

$$

\kappa(\mathbf{I}*i, \mathbf{I}*j) = \frac{\sqrt{\sum*{d=1}^D (I*{id} - I_{jd})^2}}{\epsilon}  

$$  

- **Purpose**: Quantifies distinguishability across all dimensions.

## **2. Information Density**

$$

\rho_{\mathbf{I}} = \frac{\text{Count}(\kappa \geq 1)}{\epsilon^D \cdot \Delta|\tau|}  

$$  

- **Purpose**: Measures how tightly distinguishable states are packed in $D$-dimensional space.

## **3. Time Emergence**

$$

t \propto \frac{|\tau|}{\epsilon} \quad \text{(Discrete sequence length scaled by resolution)}  

$$  

## **4. Gravity Formula**

$$

G \propto \rho_{\mathbf{I}} \cdot \kappa_{\text{avg}} \cdot \frac{d|\tau|}{d\epsilon}  

$$  

- **Purpose**: Unifies gravity as an informational effect, eliminating dark matter.

## **5. Entropy Gradient**

$$

\frac{\partial H}{\partial |\tau|} > 0 \quad \text{(Entropy increases with sequence length)}  

$$  

## **6. Causality**

$$

\lambda(\mathbf{I}_a \rightarrow \mathbf{I}_b) = \frac{P(\mathbf{I}_b | \mathbf{I}_a)}{P(\mathbf{I}_b)}  

$$  

## **7. Consciousness Threshold**

$$

\phi \propto \frac{\sum \kappa \cdot \lambda \cdot \rho}{|\tau|} \quad \text{(Requires $\phi > \phi_{\text{threshold}}$)}  

$$  

---

# **Key Cross-Concept Dependencies**

1. **Gravity Depends On**:
   - $\rho_{\mathbf{I}}$: Information density.
   - $\kappa_{\text{avg}}$: Average contrast.
   - $\epsilon$: Resolution defining sequence progression.

2. **Consciousness Depends On**:
   - $M$: Mimicry of neural patterns.
   - $\lambda$: Synaptic causality.
   - $\rho$: Repetition in brain sequences ($\tau$).

3. **Edge Networks Govern**:
   - $E_{ij}$: Links states with $\kappa \geq 1$.
   - **Example**: Quantum entanglement → $E_{ij} = 1$.

---

# **Examples Of Symbol Usage**

1. **Planetary Motion**:
   - Observations: $\mathbf{I}_k$ (position, velocity, mass).
   - **Gravity**:

     $$
     G_{\text{planets}} \propto \rho_{\mathbf{I}} \cdot \kappa_{\text{position}} \cdot \frac{d|\tau|}{d\epsilon}  
     
$$  

2. **Quantum Entanglement**:
   - **Edge Network**: $G_{\text{quantum}}$ links $\mathbf{I}_1$ and $\mathbf{I}_2$ with $\kappa \geq 1$.

3. **Consciousness in AI**:
   - **Threshold**:

     $$
     \phi_{\text{AI}} \propto \frac{\sum_{\tau} \kappa(\mathbf{I}_i, \mathbf{I}_j) \cdot \lambda \cdot \rho}{|\tau|}  

$$  

---
