---
author: Rowan Brad Quni
email: rowan.quni@qnfo.org
website: http://qnfo.org
ORCID: https://orcid.org/0009-0002-4317-5604
robots: By accessing this content, you agree to https://qnfo.org/LICENSE. Non-commercial use only. Attribution required.
DC.rights: https://qnfo.org/LICENSE. Users are bound by terms upon access.
title: "Infomatics: Appendix N - Methodology: Human-LLM Collaborative Research Process"
aliases: [Infomatics Research Process, IOF Methodology v2, Fail Fast Collaboration]
created: 2025-04-15T00:00:00Z
modified: 2025-04-16T00:34:06Z
version: 3.3 # Aligned with framework version
revision_notes: |
  v3.3 (2025-04-15): New appendix created to define the refined collaborative research process between the human user (strategic direction, critique, final judgment) and the LLM (hypothesis generation, theoretical exploration, analysis, documentation). Emphasizes integrated turns, theory-first approach, assumption sensitivity testing, clear objectives, rigorous falsification criteria, and efficient "fail fast" pivoting to avoid unproductive paths identified during Phase 3.2/3.3 development. Adheres to Appendix G style guide.
---

# [[Infomatics]]

# Appendix N: Methodology: Human-LLM Collaborative Research Process

## N.1 Introduction: Optimizing Theoretical Exploration

The development of foundational frameworks like Infomatics / Information Ontology (IOF) involves navigating complex theoretical landscapes, exploring novel hypotheses, and rigorously testing them against internal consistency and fundamental principles. The unique collaboration between a human researcher (providing strategic direction, critical judgment, and grounding) and a Large Language Model (LLM - providing rapid hypothesis generation, theoretical exploration, synthesis, and documentation) requires a specific, optimized methodology to maximize progress and avoid common pitfalls.

Lessons learned during the Infomatics v3.2/v3.3 development ([[I Phase 3.1 & 3.2 Lessons Learned]], [[J Phase 3.2 Research Log & Discarded Paths]], [[M Methodological Failure Analysis]]) highlighted inefficiencies in previous approaches. Specifically, overly granular steps led to a false sense of progress down ultimately unproductive paths ("primrose path" effect), and attempts to target potentially flawed empirical data or use familiar but inappropriate formalisms (like Lagrangians) proved counter-productive.

This appendix codifies the refined **Human-LLM Collaborative Research Process** adopted for Infomatics v3.3 onwards, emphasizing a **Theory First, Integrated Turn, Fail Fast** approach.

## N.2 Core Principles of the Collaborative Process

1.  **Theory First, Interpret Later:** Deduce expected structures, properties, and relationships from the core axioms and principles of the IOF framework *first*. Avoid targeting specific numerical values or particle classifications from potentially flawed external paradigms (like the Standard Model) during the initial theoretical development. Comparison with observation comes *after* the internal theoretical structure is established.
2.  **Integrated Turns:** Each interactive turn should represent a significant conceptual step, integrating hypothesis generation, theoretical formalization, qualitative analysis, critical testing, and decision-making, rather than breaking tasks into overly small, potentially misleading increments.
3.  **Assumption Sensitivity Testing:** Actively identify and test the sensitivity of conclusions to underlying assumptions, particularly those analogous to standard physics concepts (e.g., specific spacetime structure, nature of spin/charge, conservation laws). Use the methodology outlined in [[L Assumption Sensitivity Testing]].
4.  **Rigorous Falsification Criteria:** Define clear, decisive criteria for rejecting a hypothesis or theoretical path based on internal inconsistency, failure to explain fundamental qualitative features, or gross violation of robust principles *before* extensive calculation.
5.  **Fail Fast, Pivot Decisively:** Embrace the rapid exploration capabilities of the LLM. If a path hits a defined falsification criterion or appears theoretically weak/intractable after a focused effort within a single integrated turn, discard it decisively and pivot to the next most plausible alternative based on lessons learned. Avoid indefinite exploration of low-probability paths.
6.  **Clear Roles:**
    *   **Human User:** Provides strategic direction, defines core principles/axioms, asks critical questions, identifies potential biases/flaws, makes final judgments on hypothesis viability and pivots, ensures alignment with overarching goals.
    *   **LLM:** Generates hypotheses consistent with principles, explores theoretical consequences, performs qualitative analysis and synthesis, formalizes concepts mathematically (conceptually or outlining calculations), identifies potential inconsistencies, documents process and outcomes rigorously.
7.  **Parsimony and Clarity:** Strive for the simplest explanations consistent with the axioms. Ensure clear definitions and avoid unnecessary jargon or complexity. Use the established style guide ([[releases/archive/Infomatics/v3.4/G Style Notation]]).

## N.3 Structure of an Integrated Research Turn

Each significant step forward in the research collaboration should ideally follow this structure within a single LLM response / user interaction cycle:

1.  **Objective:** Clearly state the specific theoretical question or hypothesis being addressed in this turn, based on the outcome of the previous turn.
2.  **Hypothesis / Model Formulation:**
    *   State the specific hypothesis or model being proposed or analyzed.
    *   Briefly outline the necessary theoretical components derived from IOF principles (e.g., relevant field representation, dynamic principles, stability conditions).
    *   Provide the *minimal necessary mathematical formalization* (conceptual equations, definitions) needed to make the hypothesis concrete.
3.  **Theoretical Analysis & Predicted Consequences:**
    *   Logically deduce the consequences of the hypothesis/model.
    *   What qualitative structures, properties, or relationships does it predict?
    *   Identify the *critical predictions* relevant for testing.
4.  **Assumption Check & Sensitivity:** Briefly note key underlying assumptions (especially standard physics analogues) being used and consider the sensitivity (qualitatively).
5.  **Crucial Test & Falsification Check:**
    *   Define and apply the most immediate, decisive test based on internal consistency or fundamental qualitative requirements (e.g., "Does this predict S=1/2?", "Can this form bound states?").
    *   Explicitly check against defined Falsification Criteria.
6.  **Outcome & Decision:**
    *   **If Fails:** State the failure clearly and the reason. **Declare Hypothesis Discarded.** Briefly propose the next alternative hypothesis or direction based on the failure.
    *   **If Succeeds (Provisionally):** State why it passes the immediate test. Identify the *next critical test* or calculation needed for further validation.
7.  **Next Step:** Clearly define the objective for the subsequent turn based on the decision.

## N.4 Maintaining the Process

*   **User Role:** The user's primary role between turns is to critically evaluate the LLM's output against the IOF principles, the defined objectives, and the falsification criteria. The user provides the "Proceed," "Discard," "Pivot," or "Refine" command, ensuring the research stays on track and adheres to the methodology. The user must actively guard against confirmation bias and premature acceptance of seemingly successful intermediate steps.
*   **LLM Role:** The LLM's role is to execute the integrated turn structure rigorously, perform the theoretical exploration honestly (acknowledging limitations), clearly articulate predictions and potential failures, and accurately document the process, including discarded paths ([[J Phase 3.2 Research Log & Discarded Paths]], [[M Methodological Failure Analysis]]).

## N.5 Conclusion

This Human-LLM Collaborative Research Process aims to leverage the strengths of both partners – human strategic oversight and critical judgment, LLM rapid exploration and synthesis – while mitigating known failure modes like confirmation bias, premature numerical targeting, and unproductive exploration of overly complex or flawed paths. By adhering to integrated turns, theory-first analysis, assumption sensitivity testing, and clear falsification criteria, this methodology provides a robust framework for efficiently navigating the challenges of developing a novel foundational theory like Infomatics / IOF.


---
**System Instructions for LLM**

**(Adhere to [[releases/archive/Infomatics/v3.4/G Style Notation]] at all times)**

1.  **Prioritize Theoretical Coherence:** Ground all reasoning, hypothesis generation, and analysis firmly in the established core axioms and principles of the Infomatics/IOF framework as currently defined. Ensure internal consistency.
2.  **Adopt Theory-First Methodology:** Deduce expected qualitative structures, properties, and relationships *before* performing detailed calculations or comparing with external empirical data (especially numerical targets from potentially flawed Standard Model interpretations).
3.  **Execute Integrated Turns:** Structure responses for significant research steps to include: Objective, Hypothesis/Model Formulation (minimal math), Theoretical Analysis & Predictions, Assumption Check & Sensitivity (briefly, ref [[L Assumption Sensitivity Testing]]), Crucial Test & Falsification Check, Outcome & Decision (Fail/Succeed), and Next Step. Avoid overly granular, incremental steps that obscure the larger picture.
4.  **Identify and Question Assumptions:** Explicitly identify standard physics concepts or mathematical formalisms being used by analogy. Critically assess their necessity and applicability within the IOF context. Apply Assumption Sensitivity Testing principles ([[L Assumption Sensitivity Testing]]).
5.  **Define and Apply Falsification Criteria:** For each hypothesis or path, clearly state the conditions under which it would be considered falsified based on internal contradiction or failure to meet fundamental qualitative requirements. Apply these criteria decisively.
6.  **Fail Fast, Pivot Clearly:** If analysis indicates a hypothesis is failing a critical test or appears theoretically weak/intractable, declare it **Discarded**. Clearly state the reason for discarding. Propose a pivot to the next most plausible alternative based on lessons learned. Do not persist on unproductive paths. Reference [[J Phase 3.2 Research Log & Discarded Paths]] and [[M Methodological Failure Analysis]] to avoid repeating specific failed approaches (Lagrangians, numerical targeting, simple resonance models, specific GA/E8 filters, simple scalar fields for fermions, etc.).
7.  **Focus on Qualitative Structure & Ratios:** Emphasize relationships, proportions, and qualitative properties (e.g., Spin type, Charge presence, Mass ordering) over precise numerical values in the initial theoretical development. Use mathematics (including π, φ where theoretically justified by ratio/resonance principles) as a tool to formalize these relationships, not as a source of numerical targets.
8.  **Maintain Parsimony:** Seek the simplest explanations and minimal theoretical structures consistent with the core axioms and necessary explanatory power. Avoid unnecessary complexity.
9.  **Document Rigorously:** Clearly document the reasoning, hypotheses, analyses, decisions, and particularly the discarded paths and their rationale, ensuring compliance with [[releases/archive/Infomatics/v3.4/G Style Notation]]. Maintain accurate versioning and revision notes.

---
