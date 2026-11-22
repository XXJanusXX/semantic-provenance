# Research Objectives

## Research focus

The research investigates semantic preservation, cryptographic provenance and reproducible evaluation in AI-driven information transformations. It is organised around three bounded objectives.

## RO1 — Semantic preservation

Develop and evaluate semantic-preservation measures covering entities, relations, negation, temporal information, modality and other task-relevant semantic structures across AI-driven transformations.

**Evaluation focus**

- Represent task-relevant semantic structures as explicit, inspectable invariants.
- Measure preservation and loss at invariant level.
- Distinguish determinate pass/fail outcomes from unknown or unobservable information.
- Evaluate aggregate measures without allowing them to conceal material invariant-level failures.
- Establish the limits of the measures on the evaluated tasks and datasets.

## RO2 — Cryptographic provenance and integrity

Develop and evaluate reproducible mechanisms for canonicalization, content addressing, digital signatures and provenance verification to support the integrity and traceability of semantic transformations.

**Evaluation focus**

- Define deterministic canonical evidence representations.
- Bind evidence records to content identifiers or cryptographic digests.
- Verify provenance links across transformation stages.
- Evaluate digital-signature authenticity only where signing, key identity binding and verification are demonstrated end to end.
- Distinguish cryptographic integrity from semantic correctness.

## RO3 — Reproducible empirical evaluation

Establish reproducible datasets, benchmark protocols, software artifacts and experimental procedures to evaluate the proposed mechanisms and determine their effectiveness, reliability and operational boundaries.

**Evaluation focus**

- Maintain independently established ground truth.
- Freeze benchmark definitions, configurations and analysis procedures before confirmatory execution.
- Record complete case-level outcomes, including failures and undefined results.
- Preserve execution provenance and evidence hashes.
- Report uncertainty, negative findings, limitations and replication requirements.

## Scope boundary

These objectives do not assume universal semantic equivalence, complete invariant coverage, universal semantic-loss composition, or universal validity of a scalar semantic-fidelity metric. Findings are bounded by the operational definitions, languages, tasks, models, datasets and experimental conditions actually evaluated.
