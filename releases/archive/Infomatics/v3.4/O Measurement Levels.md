---
author: Rowan Brad Quni
email: rowan.quni@qnfo.org
website: http://qnfo.org
ORCID: https://orcid.org/0009-0002-4317-5604
robots: By accessing this content, you agree to https://qnfo.org/LICENSE. Non-commercial use only. Attribution required.
DC.rights: https://qnfo.org/LICENSE. Users are bound by terms upon access.
title: "Infomatics: Appendix O - Levels of Measurement in Physical Description"
aliases: [Infomatics Measurement Levels, IOF Measurement Scales]
created: 2025-04-15T00:00:00Z
modified: 2025-04-16T01:29:54Z
version: 3.3 # Aligned with framework version
revision_notes: |
  v3.3 (2025-04-15): New appendix created to discuss the relevance of Stevens' levels of measurement (Nominal/Categorical, Ordinal, Interval, Ratio) to the development and interpretation of the Infomatics/IOF framework. Highlights how the framework's predictions are often most robust at the Categorical and Ordinal levels, while Ratio-level predictions (like mass ratios) are key tests, and Interval-level assumptions should be treated with caution. Connects to critiques of standard metrology. Adheres to Appendix G style guide.
---

# [[Infomatics]]

# Appendix O: Levels of Measurement in Physical Description

## O.1 Introduction: Beyond Numbers

The process of describing physical reality inevitably involves measurement and quantification. However, as highlighted by the critiques motivating the Infomatics/IOF framework ([[releases/2025/Infomatics/B Crosswalk]], [[Modern Physics Metrology]]), the *way* we measure and the *mathematical structures* we use (numbers, scales) are not neutral observers but can shape our understanding and potentially introduce artifacts. Stevens' levels of measurement provide a useful classification scheme (Nominal/Categorical, Ordinal, Interval, Ratio) for understanding the information content and limitations of different types of scales. This appendix discusses the relevance of these levels to the interpretation of Infomatics/IOF predictions and the critique of standard physics metrology. Recognizing the appropriate level of measurement for theoretical predictions is crucial for avoiding category errors and ensuring robust analysis.

## O.2 Levels of Measurement (Stevens, 1946)

**Categorical (Nominal) Scale:** Assigns labels or categories without inherent order. Operations: Equality/Inequality. Examples: Particle types (electron, proton), charge sign (+/-), quark flavors (up, down).

**Ordinal Scale:** Ranks categories in a meaningful order, but the intervals between ranks are not necessarily equal or meaningful. Operations: Equality, Inequality, Greater/Less Than. Examples: Complexity levels (Î₁, Î₂, Î₃...), Mohs hardness scale, finishing positions in a race.

**Interval Scale:** Orders categories with equal intervals between them, allowing meaningful comparison of differences. Lacks a true, meaningful zero point. Operations: Equality, Inequality, Greater/Less Than, Addition/Subtraction of intervals. Examples: Temperature in Celsius/Fahrenheit, calendar dates, standard IQ scores.

**Ratio Scale:** Orders categories with equal intervals and possesses a true, meaningful zero point, allowing meaningful ratios between measurements. Operations: All arithmetic operations (Equality, Inequality, Order, Addition/Subtraction, Multiplication/Division, Ratios). Examples: Mass in kg, Length in meters, Energy in Joules, Temperature in Kelvin, particle counts.

## O.3 Relevance to Infomatics/IOF Framework

The development of Infomatics v3.3 revealed the importance of distinguishing these levels when interpreting theoretical predictions derived from its core principles (Informational Field $\mathcal{F}$, π-φ Ratio Resonance):

**Robust Categorical & Ordinal Predictions:**
*   The framework most robustly predicts the **existence of distinct categories** of stable resonant patterns {Î₁, Î₂, Î₃,...}.
*   It predicts a natural **ordinal ranking** of these states based on increasing complexity derived from the Ratio Resonance condition.
*   This ordinal complexity is theorized to map directly to **ordinal properties**:
    *   Mass: $M_1 < M_2 < M_3 < ...$
    *   Spin: $S_1 < S_2 < S_3 < ...$ (corresponding to predicted categories S=0, S=1/2, S=1...).
*   Charge is predicted **categorically** (Q=0 vs Q≠0) based on the structure's symmetry or topology.

**Crucial Ratio-Level Predictions:**
*   The fundamental stability condition itself ($\phi^{m'} \approx \pi^{k'}$) is based on achieving an optimal **ratio** between scaling and cyclical aspects, linked to the fundamental **ratio constants** π and φ.
*   The framework makes specific predictions about **mass ratios** (e.g., M₂/M₁, M₃/M₂) which are hypothesized to emerge from the dynamics and potentially involve φ. These ratios are critical quantitative tests.
*   Predicted **charge values** (Q=0, Q=±e<sub>IO</sub>) represent ratio-level information relative to a fundamental charge unit e<sub>IO</sub>.

**Caution Regarding Interval-Level Assumptions:**
*   Previous failures often occurred when implicitly assuming **interval-level** properties without justification. For example, assuming the complexity levels *i* in Î<sub>i</sub> represent equal "steps," or assuming mass scales linearly with some simple integer index *k* ($M \propto k$) or even exponentially with an integer index ($M \propto \phi^k$) where *k* increments by one unit per state.
*   The Infomatics v3.3 approach avoids this by deriving the ordinal sequence first and treating specific scaling laws (like $M_i \propto \phi^{m'_i}$) as ratio-level hypotheses to be tested by calculation, not assumed *a priori*. The "interval" between M₁ and M₂ might be vastly different from that between M₂ and M₃ in ways not captured by simple integer steps.

## O.4 Connection to Critique of Standard Metrology

This perspective aligns with the critique of standard physics and metrology:

*   **Arbitrary Units (Interval/Ratio Issues):** Standard physics relies heavily on ratio-level measurements (kg, m, s, J) defined by the SI system. However, the critique in [[2-7 Standard Units]] argues that fixing constants like *c* and *h* introduces artificial rigidity and potential artifacts into this ratio system, potentially distorting our perception of physical ratios.
*   **Over-reliance on Numerical Values:** The focus on precise numerical values (interval/ratio level) in standard physics, while necessary for prediction, can sometimes obscure underlying categorical or ordinal structure, or lead to chasing numerical coincidences (as argued regarding $\hat{\alpha}$ derivations).
*   **Information Ontology Focus:** IOF/Infomatics attempts to ground physics in more fundamental categorical (types of patterns), ordinal (complexity sequence), and ratio (π-φ balance, emergent mass/charge ratios) relationships inherent in the informational field, before necessarily translating fully into the potentially artifact-laden SI ratio scales.

## O.5 Methodological Implications

Understanding these levels guides the IOF/Infomatics research methodology:

1.  **Prioritize Qualitative Structure:** First, establish the predicted **categories** (S, Q types) and **order** (Mass, Spin sequence) of stable states based on theoretical principles.
2.  **Derive Ratios:** Focus on calculating fundamental **dimensionless ratios** (Mass ratios, coupling ratios) as the primary quantitative predictions emerging from the theory.
3.  **Test Structure:** Compare the predicted categorical, ordinal, and ratio structures with the qualitative features and robust quantitative ratios observed in nature.
4.  **Avoid Premature Interval Assumptions:** Do not assume equal intervals or simple linear/exponential scaling with integer indices unless rigorously derived.
5.  **Connect to SI Cautiously:** Translate predictions into standard SI units only when necessary for comparison with specific experiments, being mindful of the potential artifacts embedded in the SI system itself (fixed c, h).

By respecting the different levels of measurement and prioritizing the derivation of categorical, ordinal, and ratio properties first, the IOF/Infomatics framework aims to build a more robust and less assumption-laden description of physical reality.
