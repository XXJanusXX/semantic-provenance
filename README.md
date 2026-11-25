# Semantic Provenance

**Semantic Preservation, Cryptographic Provenance and Reproducible Evaluation in AI-Driven Information Transformations**

This repository is the public research and software home for work investigating how task-relevant meaning can be measured across AI-driven information transformations, how transformation evidence can be made verifiable, and how these mechanisms can be evaluated reproducibly.

The research is organised around three objectives:

1. Develop and evaluate semantic-preservation measures covering entities, relations, negation, temporal information, modality and other task-relevant semantic structures.
2. Develop reproducible mechanisms for canonicalization, content addressing, digital signatures and provenance of semantic transformations.
3. Produce reproducible datasets, benchmark protocols, software artifacts and empirical evidence sufficient to support or reject the proposed hypotheses.

The work uses **LENS (Language, Enterprise, Networked Semantics)** as its research framework. The repository is intended to make the research questions, methods, software, evidence, limitations and citation information accessible to researchers and practitioners.

## Research questions

- **RQ1 — Semantic preservation:** To what extent can structured semantic-preservation measures detect and quantify the preservation or loss of task-relevant semantic information across AI-driven transformations?
- **RQ2 — Cryptographic provenance and integrity:** To what extent can canonicalization, content addressing, digital signatures and provenance verification provide reproducible evidence of integrity and traceability across semantic transformation workflows?
- **RQ3 — Reproducible evaluation:** How can reproducible datasets, benchmark protocols and experimental procedures be designed to evaluate the effectiveness, reliability and limitations of semantic-preservation and provenance mechanisms?

## Research hypotheses

The research has one primary hypothesis and three secondary hypotheses.

- **H1 (primary):** Explicit semantic governance produces a statistically significant improvement in semantic fidelity compared with the direct transformation baseline.
- **H2 (secondary):** Explicit semantic governance significantly reduces the reconciliation failure rate compared with the direct transformation baseline.
- **H3 (secondary):** The semantic invariant-based detection mechanism achieves the prespecified detection performance on positive semantic-loss boundary cases.
- **H4 (secondary):** Adding conventional cryptographic provenance and integrity mechanisms significantly improves provenance continuity compared with the semantic-governance condition without those mechanisms.

The corresponding null hypotheses, endpoint definitions, comparison conditions, performance thresholds and statistical procedures are specified in the controlled research protocol and statistical analysis plan. The statements above are research propositions, not claims that the hypotheses have already been supported.

## Research contributions

### 1. Semantic-preservation measurement

A structured semantic-invariant approach for evaluating the preservation and loss of task-relevant information across AI-driven transformations. Relevant semantic structures include entities, relations, constraints, polarity, temporal information, quantification, modality, policy, event semantics and quantities or units.

### 2. Verifiable transformation provenance

A reproducible technical approach to canonical evidence representation, content addressing, cryptographic integrity and provenance verification across transformation workflows. Digital-signature authenticity is claimed only to the extent demonstrated by end-to-end implementation and verification evidence.

### 3. Reproducible empirical evaluation

A benchmark and experimental methodology for evaluating semantic-preservation and provenance mechanisms, including their limitations, failure modes and operational boundaries.

## Research status and interpretation

This repository is the public-facing research home. Publication of a research question or hypothesis does not imply that its experiment has been completed or that its claim has been validated.

Confirmatory evaluation, including the SCI-12 experimental programme, remains subject to its controlled protocol, benchmark and independent ground-truth requirements, statistical analysis plan, and explicit execution authorisation. No confirmatory result should be inferred from the existence of code, tests, fixtures or documentation alone.

Results will be reported with their applicable conditions, denominators, uncertainty, exclusions, undefined outcomes and limitations. A successful integrity or provenance check does not establish semantic correctness. Cryptographic provenance and distributed-ledger anchoring, where used, are not substitutes for semantic validation.

## Repository map

The research documentation is organised as follows:

- [Research objectives](docs/research/research-objectives.md)
- [Research questions](docs/research/research-questions.md)
- [Research hypotheses](docs/research/research-hypotheses.md)
- [Research contributions](docs/research/research-contributions.md)
- [Research boundaries and limitations](docs/research/research-boundaries.md)

Implementation, benchmark data, protocols and evidence will be published in their respective directories as they are prepared for public release. Third-party datasets, models and dependencies retain their own licence terms.

## Architecture and experimental design

The repository includes two editable Mermaid source figures, designed for A4 landscape export:

- [Figure 1 — LENS high-level architecture](docs/architecture/figure-1-lens-high-level-architecture.mmd): the three core research layers and supporting architectural capabilities.
- [Figure 2 — Experimental conditions and hypothesis mapping](docs/architecture/figure-2-experimental-conditions-hypothesis-mapping.mmd): B0–B5 conditions, H1–H4 comparisons, and evidence reconciliation.

**Figure captions for the DBA proposal**

1. *Figure 1. High-Level Architecture of the LENS Framework.*
2. *Figure 2. LENS Experimental Conditions, Hypothesis Mapping and Evidence Reconciliation.*

Both figures represent the proposed research design. B5/DLT is optional and deferred from the core confirmatory design. The diagrams do not imply that confirmatory experiments have been executed or authorised.

## Reproducibility and evidence principles

- Keep detector outputs separate from independently established ground truth.
- Preserve case-level accounting, including failed executions and undefined outcomes.
- Record software versions, configurations, inputs and evidence hashes.
- Distinguish exploratory, pilot and confirmatory results.
- Report negative and inconclusive results alongside positive findings.
- Do not generalise beyond the evaluated languages, tasks, models, conditions or datasets.

## Licensing and citation

The repository's original software and documentation are released under the [Apache License 2.0](LICENSE), subject to the rights of the relevant copyright holders and any separately licensed third-party materials.

If you use this repository, cite it using [CITATION.cff](CITATION.cff). Dataset and model citations and licence obligations must be followed independently.

## Author

Siddarth Laxminarayanan

## Disclaimer

This repository is a research and software project. It does not provide a guarantee of semantic equivalence, complete semantic-loss detection, universal interoperability, or cryptographic security beyond the properties explicitly specified and empirically verified.
