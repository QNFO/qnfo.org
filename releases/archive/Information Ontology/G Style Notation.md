---
author: Rowan Brad Quni
email: rowan.quni@qnfo.org
website: http://qnfo.org
ORCID: https://orcid.org/0009-0002-4317-5604
robots: By accessing this content, you agree to https://qnfo.org/LICENSE. Non-commercial use only. Attribution required.
DC.rights: https://qnfo.org/LICENSE. Users are bound by terms upon access.
title: "Infomatics: Appendix G - Style and Notation Conventions"
aliases: [Infomatics Style Guide, Infomatics Notation, Infomatics Conventions]
created: 2025-04-15T15:45:00Z
modified: 2025-04-15T02:40:15Z
version: 3.0 # Aligned with framework version
revision_notes: |
  v3.0.11 (2025-04-15): Added specific guidelines for Table of Contents formatting (G.2.2.1) and reinforced correct wiki link usage in G.2.13 based on successful ToC generation. Final guide for v3.0.
  v3.0.10 (2025-04-15): Corrected G.2.13 (Cross-referencing) to specify the correct Obsidian wiki link format for internal heading links (`[[#Heading Text]]`) vs. external file links (`[[File Name]]`). Ensured self-compliance.
  v3.0.9 (2025-04-15): Corrected G.2.13 (Cross-referencing) to distinguish between internal heading links (within the consolidated main document) and external file links (for separate appendices). Updated file naming G.2.8 context.
  v3.0.8 (2025-04-15): Added guideline G.2.13 on using Obsidian wiki links for internal cross-referencing (heading links within main doc, file links for separate appendices). Updated file naming G.2.8 context.
  v3.0.7 (2025-04-15): Added guideline G.2.9 (Revision History Integrity), G.2.10 (Typographic Quotes), G.2.11 (Numbers), G.2.12 (Units), G.2.13 (Cross-referencing - now G.2.14), G.2.14 (Tense - now G.2.15). Clarified file naming convention (G.2.8) allows spaces.
  v3.0.6 (2025-04-15): Added guideline G.2.15 explicitly prohibiting unauthorized truncation or paraphrasing of content during generation or revision.
  v3.0.5 (2025-04-15): Final self-compliance revision. Replaced all internal bullet points with paragraph blocks or bolded lead terms per rule G.2.5. Ensured the guide itself now adheres to the specified list style.
  v3.0.4 (2025-04-15): Removed final "Conclusion" section (G.4) to ensure self-compliance with style guide discouraging overuse of "Conclusion". Integrated sentiment into G.1.
  v3.0.3 (2025-04-15): Added guidelines on section endings, minimum subsection length, and refined tone/vocabulary guidelines to explicitly avoid common AI tells. Reinforced list usage restrictions.
  v3.0.2 (2025-04-15): Major revision based on user feedback. Reordered Style before Notation. Eliminated 'meas'/'eff'/'EM' subscripts, introduced hat notation (\hat{\alpha}), base symbols for Infomatics values, and 'S' for Standard. Revised list conventions. Confirmed heading capitalization. Updated symbol for Geometric Amplitude (\mathcal{A}).
  v3.0.1 (2025-04-15): Revised capitalization rules for headings. Updated file naming convention.
  v3.0 (2025-04-15): Initial creation of Appendix G.
---

# [[Infomatics]]

# Appendix G: Style and Notation Conventions

## G.1 Purpose

This appendix establishes the style and notation conventions to be used throughout the Infomatics Operational Framework documentation. Adherence to these guidelines ensures clarity, consistency, professional presentation, and authenticity, facilitating easier reading, understanding, and future maintenance. These conventions apply to the main framework document and any associated separate appendix or supplementary files. These conventions provide a baseline for consistency and may be refined in future versions as the framework develops, with changes documented in the main document's revision history.

## G.2 Style Conventions

### G.2.1 Tone and Vocabulary

**Tone:** Maintain a formal, objective, precise, and rigorous scientific tone appropriate for a foundational physics document.

**Vocabulary:** Strive for clarity and conciseness. Use precise technical terms where necessary (defined in the [[releases/archive/Infomatics/v3.4/D Glossary]]). Avoid jargon where simpler language suffices.

**Avoiding AI Tells:** Actively avoid common patterns often found in AI-generated text. This includes avoiding repetitive introductory or concluding phrases (e.g., “It is important to note,” “In conclusion,” “Furthermore,” “Moreover”); vary sentence structure instead. Avoid overuse of vague adjectives like “significant,” “crucial,” “notable,” “remarkable,” “intriguing” unless the significance is explicitly demonstrated or quantified; be specific. Favor clear and direct sentence structures over overly complex or convoluted ones. Aim for original expression and avoid clichés or overly common scientific platitudes.

### G.2.2 Headings and Structure

**Hierarchy:** Use standard Markdown heading levels (`#`, `##`, `###`, `####`) to create a clear hierarchy.
`# Document Title`: Title Case.
`## Part X: Title Case`
`## Appendix L: Title Case`
`### Section N: Sentence case title` (e.g., `### Section 1: Introduction and motivation`)
`#### N.M Subsection: Sentence case title` (e.g., `#### 1.1 Motivation: Cracks in the standard edifice`)

**Flow:** Maintain the logical flow outlined in the main document's Table of Contents.

**Subsection Length:** Avoid creating subsections that contain only a single short paragraph or block of text, unless logically essential for demarcation (e.g., stating a formal Axiom). Combine related short points into more substantial subsections to improve flow and reduce fragmentation.

**Section Endings:** Avoid repetitive use of “Conclusion.” Favor more descriptive section endings like “Summary,” “Synthesis,” “Implications,” or integrate concluding thoughts into the final paragraph without a dedicated subheading where appropriate.

**Table of Contents (ToC):**
*   **Heading:** Use `## Table of Contents`.
*   **Format:** Use a nested bulleted list (`*`). Top-level items should correspond to major Parts (e.g., `Part 1: Foundations...`), formatted in bold but **not** linked.
*   **Content:** Under each Part, list only the major Sections (e.g., `Section 1: ...`, `Section 2: ...`). Include a final top-level item for Appendices. List only the main Appendices (A, B, C...). Do **not** include subsections in the ToC.
*   **Linking:** Use internal wiki links for Sections and external wiki links for Appendices, following the rules in [[#G.2.13 Cross-referencing (Wiki Links)]].

### G.2.3 Capitalization

**Headings:** Follow the case conventions defined in [[#G.2.2 Headings and Structure]].

**Proper Nouns:** Capitalize standard proper nouns (Infomatics, General Relativity, Standard Model, Planck, Lucas, Bohr, Heisenberg, etc.) and specific named hypotheses when first introduced or emphasized (e.g., L<sub>m</sub> Primality Hypothesis).

**Acronyms:** Use standard capitalization for acronyms (GR, SM, QM, QED, BBN, CMB, SNe, BDT, etc.). Define upon first use if not universally common.

**Core Concepts:** Capitalize the full names of core Infomatics concepts when first defined or treated as specific terms of art (e.g., Universal Information Field, Potential Contrast, Manifest Information, Resolution, Geometric Amplitude). The corresponding symbols (I, κ, Î, ε, $\mathcal{A}$) are used subsequently.

**Standard Usage:** Follow standard English capitalization rules for sentence beginnings and proper nouns within sentences. Avoid unnecessary capitalization of common nouns (e.g., “field”, “particle”, “constant”, “principle” unless part of a proper name like “Planck constant”).

### G.2.4 Emphasis

**Bold:** Use for first definition of key terms (as in Axioms), highlighting core hypotheses, and occasionally for strong emphasis on critical concepts. Use sparingly. Use for lead terms in definition lists or paragraph-block lists where appropriate (see [[#G.2.5 Lists]]). Also used for Part headings in the ToC.

**Italics:** Use primarily for variables when mentioned within prose to distinguish them from surrounding text (e.g., “the index *m* determines mass”). Use sparingly for emphasis or foreign words.

### G.2.5 Lists

**General Principle:** Prefer prose or paragraph blocks over itemized lists whenever possible to maintain a narrative flow.

**Bulleted Lists (`*` or `-`):** Use **only** for unordered lists of short items (individual words or very short phrases where parallel structure is beneficial, e.g., the Table of Contents). Do **not** use for sentences or paragraphs. Limit frequency.

**Numbered Lists (`1.`, `2.`):** Use **only** for sequential steps (e.g., in a derivation or methodology), ordered lists of short items, or enumerated arguments where numerical order is critical and items are concise. Do **not** use for paragraphs. Limit frequency.

**Paragraph Block Lists:** For lists where items require explanation (sentences or paragraphs), format as distinct paragraphs. If helpful for clarity (like in a glossary or defining components), the lead term or phrase may be bolded, followed by the explanatory text. This is the preferred method for itemizing complex points.

### G.2.6 Terminology

Use terms consistently as defined in the [[releases/archive/Infomatics/v3.4/D Glossary]]. Avoid jargon where simpler language suffices, but use precise technical terms when necessary.

### G.2.7 References and Citations

Currently uses informal placeholders (e.g., `[Ref: Internal Note]`, `[[Appendix X]]`). For future formal publication, standard citation practices (e.g., numerical, author-date) should be adopted consistently.

### G.2.8 File Naming (for Separate Files)

This convention applies primarily if/when sections or appendices are maintained as separate files. Use the format: `Identifier Title.md`, where `Identifier` is the Section number (e.g., `1`) or Appendix letter (e.g., `A`) and `Title` is a concise, one-to-two-word description (e.g., `1 Introduction.md`, `A Amplitude.md`, `G Style Notation.md`). **Spaces are permitted; underscores are not preferred.** The main consolidated framework document follows a more descriptive naming convention (e.g., `Infomatics Framework v3.0 Main.md`).

### G.2.9 Revision History Integrity
**Maintain Complete History:** The `revision_notes` field in the YAML front matter of the main document (or individual files, if used) is critical. It must contain a complete, chronological record of all significant changes made between versions. Entries should be dated, specify the version number, and clearly describe the modifications. **This history must never be truncated.**

### G.2.10 Typographic Quotes
**Use Curly Quotes:** Prefer proper typographic (“curly”) quotation marks (`“”` for double, `‘’` for single) over straight quotes (`"`, `'`) for actual quotations or scare quotes. Acknowledge that plain text editors or Markdown renderers may not always display these correctly, but the source should use them where appropriate. Straight quotes are acceptable for code or technical contexts where they have specific meaning.

### G.2.11 Numbers
**Numeral Usage:** Follow standard scientific convention: spell out numbers one through nine; use numerals for 10 and above. Exceptions: Always use numerals for precise measurements, percentages, units of time/measurement, and version numbers. Always spell out numbers that begin a sentence.

### G.2.12 Units
**SI Units:** Use standard SI units when presenting results that interface with standard physics or experimental data (e.g., GeV for mass when comparing). Ensure a space between the numerical value and the unit symbol (e.g., `2 GeV`, not `2GeV`). Note that core Infomatics constants (π, φ) and derived quantities (ε, $\mathcal{A}$, α) are often dimensionless.

### G.2.13 Cross-referencing (Wiki Links)
**Use Wiki Links:** Employ Obsidian-style wiki links (`[[...]]`) for internal cross-references within and between documents.
*   **Internal Links (Within Main Document):** Link directly to headings using the format `[[#Full Heading Text Exactly as Written]]`. Example: `[[#Section 3: The (n, m) resonance structure and emergent properties]]`. Ensure the heading text within the link *exactly* matches the target heading, including case and punctuation, for the link to resolve correctly in Obsidian. The Table of Contents ([[#G.2.2 Headings and Structure]]) uses this format for linking to Sections.
*   **External Links (To Separate Appendix Files):** Link to the appendix file name (without the `.md` extension), following the convention in [[#G.2.8 File Naming (for Separate Files)]]. Example: "detailed in [[A Amplitude]]" or "defined in the [[releases/archive/Infomatics/v3.4/D Glossary]]". The Table of Contents uses this format for linking to Appendices.

### G.2.14 Tense
**Consistent Tense:** Use present tense for describing the established principles, definitions, and consequences of the Infomatics framework (e.g., “Infomatics posits...”, “Mass scales as...”). Use past tense when discussing the historical development of the framework, previous versions, specific calculations performed, or standard physics concepts being critiqued (e.g., “Planck introduced...”, “Phase 2 analysis suggested...”).

### G.2.15 Content Integrity
**No Unauthorized Truncation or Paraphrasing:** During generation or revision, the full text and metadata must be presented unless explicitly agreed otherwise. Content should not be truncated (e.g., using “[...]”) or substantially paraphrased without clear indication and user consent, to ensure completeness and traceability.

## G.3 Notation Conventions

### G.3.1 General Principles
The primary goal is clarity and parsimony, avoiding ambiguity. Standard mathematical and physical notation is preferred where applicable. Notation should be defined clearly, either contextually or within this guide/the [[releases/archive/Infomatics/v3.4/D Glossary]].

### G.3.2 Subscript Policy

**Strict Prohibition:** Multi-letter or word-based subscripts are strictly prohibited.

**Preference Order:** Meaning should be conveyed primarily through the following, in order of preference:
1.  **Context:** The surrounding text should make the meaning clear whenever possible.
2.  **Standard Single-Letter Symbols/Indices:** Use widely accepted single-letter subscripts or standard symbols (see [[#G.3.4 Standard Single-Letter Subscripts and Symbols (Contextual/Glossary Definition)]]).
3.  **Explicitly Defined Single-Letter Designators:** If a distinction *must* be made using a non-standard single-letter subscript, it must be explicitly defined upon first use or within this appendix (see [[#G.3.3 Specific Symbol Definitions and Distinguishing Notation]]).

**Typographical Alternatives:** Consider standard typographical alternatives (hats, bars, calligraphic letters) before resorting to non-standard subscripts.

### G.3.3 Specific Symbol Definitions and Distinguishing Notation

**Geometric Amplitude:** The core calculated probability amplitude in Infomatics is denoted by the calligraphic symbol: $\mathcal{A}$.

**Measured/Empirical Values:** Use a hat symbol (circumflex) to denote an empirically measured value used for comparison, consistent with statistical notation. Example: $\hat{\alpha}$ (Measured Fine-Structure Constant).

**Infomatics Derived/Effective Values:** Use the base symbol (e.g., $\alpha$, $G$, $C$) for the value derived within or pertaining to the Infomatics framework. Context must differentiate it from the standard value or the measured value ($\hat{\alpha}$). Example: “The Infomatics effective coupling $\alpha$ is contrasted with the measured value $\hat{\alpha}$.”

**Standard Framework Values:** Use the subscript `S` to denote quantities associated with the *Standard* framework (e.g., Standard Model, General Relativity) only when explicit comparison is necessary and context is insufficient. Example: $G_S$ (Standard Gravitational Constant), $C_S$ (Standard Coefficient). Must be defined upon first use.

**Force/Context Specificity:** Avoid subscripts like `EM`. Rely on context (e.g., “The electromagnetic amplitude $\mathcal{A}$...”) or define temporary symbols locally if absolutely necessary within a complex equation.

### G.3.4 Standard Single-Letter Subscripts and Symbols (Contextual/Glossary Definition)
The following standard single-letter subscripts and symbols are used, with their meaning generally clear from context or defined in the [[releases/archive/Infomatics/v3.4/D Glossary]]:

**Particle Symbols:** `e, μ, τ, u, d, s, c, b, t, γ, ν, W, Z, H` used as subscripts on mass ($M$) or mass index ($m$) (e.g., $m_e$, $M_{\mu}$).

**Planck Scale:** `P` used as a subscript for Planck units (e.g., $\ell_P, t_P, m_P, E_P$).

**State Indices:** `i` (initial), `f` (final), `γ` (mediator) used as subscripts on state parameters like $n, m$.

**Sequence Index:** `m` used as the index for Lucas Numbers ($L_m$).

**Tensor Indices:** `μ, ν` (and potentially others) used for standard tensor notation (e.g., $T_{\mu\nu}$).

**Cosmological Densities:** `m` (matter), `r` (radiation), `vac` (vacuum) used as subscripts for density $\rho$ (e.g., $\rho_m, \rho_r, \rho_{vac}$).

**Standard Symbols:** Standard symbols like $\hbar$ (when discussing standard physics for comparison/replacement), $c$ (standard value context), $G$ (standard value context), $k$ (Boltzmann or proportionality constant), $i$ (imaginary unit), $e$ (elementary charge in standard context) are used where appropriate and contextually clear.

### G.3.5 Formulas
Formulas should adhere to the following:
**Display:** Significant equations should be displayed on separate lines for clarity.
**Notation:** Use standard LaTeX mathematical notation within Markdown (e.g., via MathJax or similar rendering).
**Numbering:** Numbering of equations is currently omitted for simplicity but may be introduced if extensive cross-referencing becomes necessary.