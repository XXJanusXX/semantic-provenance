# Research Hypotheses

## Hypothesis structure

The research uses one primary hypothesis and three secondary hypotheses. RQ3 is methodological and is evaluated through reproducibility criteria rather than a separate confirmatory statistical hypothesis.

The hypothesis statements below are concise public formulations. Exact estimands, comparison conditions, endpoint operationalisations, eligibility rules, thresholds, missing-outcome handling, multiplicity procedures and statistical tests must be taken from the frozen Statistical Analysis Plan (SAP) before confirmatory execution.

## H1 — Primary: Semantic fidelity

**Alternative hypothesis (H1):** Explicit semantic governance produces a statistically significant improvement in semantic fidelity compared with the direct transformation baseline.

**Null hypothesis (H0₁):** Explicit semantic governance does not produce a statistically significant improvement in semantic fidelity compared with the direct transformation baseline.

H1 is the sole primary hypothesis.

## H2 — Secondary: Reconciliation failures

**Alternative hypothesis (H2):** Explicit semantic governance significantly reduces the reconciliation failure rate compared with the direct transformation baseline.

**Null hypothesis (H0₂):** Explicit semantic governance does not significantly reduce the reconciliation failure rate compared with the direct transformation baseline.

## H3 — Secondary: Semantic-loss detection

**Alternative hypothesis (H3):** The semantic invariant-based detection mechanism achieves the prespecified detection performance on positive semantic-loss boundary cases.

**Null hypothesis (H0₃):** The semantic invariant-based detection mechanism does not achieve the prespecified detection performance on positive semantic-loss boundary cases.

The prespecified performance criterion and positive-case definition must be frozen before confirmatory evaluation. Detection claims are bounded by the tested case classes and ground-truth authority; they do not imply complete detection of all possible semantic loss.

## H4 — Secondary: Provenance continuity

**Alternative hypothesis (H4):** Adding conventional cryptographic provenance and integrity mechanisms significantly improves provenance continuity compared with the semantic-governance condition without those mechanisms.

**Null hypothesis (H0₄):** Adding conventional cryptographic provenance and integrity mechanisms does not significantly improve provenance continuity compared with the semantic-governance condition without those mechanisms.

## RQ3 reproducibility criteria

RQ3 is assessed through documented criteria rather than an additional confirmatory hypothesis:

- Deterministic execution under frozen configurations.
- Independent ground truth and detector-output separation.
- Reproducible metric calculation.
- Complete case-level accounting, including failed and undefined outcomes.
- Traceable software versions, configurations, inputs and evidence records.
- Documented limitations and independently reviewable results.

## Interpretation safeguards

- H1 remains the only primary hypothesis.
- H2, H3 and H4 are secondary hypotheses.
- No additional hypothesis is implied for exploratory interoperability or DLT work.
- Statistical significance alone does not establish practical importance, generalisability or theoretical universality.
- A hypothesis is not considered supported merely because software tests pass or a benchmark executes successfully.
- The controlled SAP governs all confirmatory endpoint and analysis details. This document must be reconciled with the approved protocol before use as an authoritative confirmatory specification.
