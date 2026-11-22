# Research Boundaries and Limitations

## Purpose

This document defines public claim boundaries for the research. It is intended to prevent the repository's research descriptions from exceeding the implementation and evidence available.

## Semantic preservation

- The semantic-invariant set is an operational representation of selected task-relevant structures, not a proof of complete semantic coverage.
- Semantic fidelity and semantic loss are bounded operational measures.
- Aggregate scores must be interpreted alongside invariant-level outcomes and unknown or unobservable states.
- No universal semantic-equivalence theorem or universal scalar semantic metric is claimed.
- Generalisation is limited to the languages, tasks, models, datasets and conditions actually evaluated.

## Cryptographic provenance

- Hash equality supports a content-integrity conclusion only for the exact canonical representation and digest procedure used.
- Provenance continuity requires verifiable links across the relevant transformation stages.
- Digital signatures support authenticity claims only when signing keys, identity binding, signing operations and verification are properly implemented and evidenced.
- Cryptographic integrity does not establish semantic correctness.
- Distributed-ledger anchoring, if evaluated, does not independently prove the truth or quality of the anchored content.

## Empirical evidence

- Pilot, exploratory and confirmatory evidence must be labelled distinctly.
- Confirmatory claims require frozen protocols, benchmark definitions, independent ground truth and the applicable analysis plan.
- Failed executions, missing outcomes, unknown classifications and exclusions must be reported transparently.
- A successful software test suite or CI workflow is not equivalent to scientific validation.
- Negative and inconclusive findings are valid research outcomes and must not be omitted.

## Reproducibility

Reproducibility claims should identify the software version, configuration, environment, dataset version, execution procedure and evidence artifacts required to reproduce the result. Reproduction by the original author should be distinguished from independent replication.

## Scope exclusions and extensions

Multilingual representation comparisons, agent interoperability, enterprise adoption studies and distributed-ledger comparisons may be valuable extensions. They are not treated as completed contributions or confirmatory claims unless the corresponding implementations, evaluation designs and evidence are published.

## Third-party materials

Datasets, pretrained models, dependencies, specifications and other third-party materials may have separate licence, attribution, access and usage conditions. The repository's Apache-2.0 licence does not relicense those materials or grant rights that the repository author does not hold.
