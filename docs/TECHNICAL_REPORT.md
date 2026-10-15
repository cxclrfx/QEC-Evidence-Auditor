# Technical Report — Standard Mathematical V1

## Purpose and evidence chain

The intended chain is declared input → Auditor calculation → structured evidence → separate Verifier calculation against the declared input → scoped decision. The verifier is described as using a separate calculation engine. This is computational separation, not a claim of organizational independence or proven absence of shared defects.

## Mathematical contracts

| Mode | Conventional foundation | Critical boundary |
|---|---|---|
| claims | Recalculation of supported parity, count and declared-condition witnesses | Unsupported assertions cannot acquire authority merely by appearing in a report |
| css | Binary linear algebra: commutation, ranks and syndrome compatibility | Matrix consistency does not prove general distance or decoding optimality |
| data | Deterministic matching of identified records | Duplicate keys introduce ambiguity; upstream completeness is a separate claim |
| finite | Enumeration within a supplied finite state model | Conclusions are relative to that model, not all physical states |
| residual | Integer modular arithmetic on declared bounded expressions | No general cryptographic or hardware guarantee follows |

Exact accepted schemas, bounds, command syntax and error handling belong to the separately delivered product contract. They are not reconstructed from the showcase text.

## Integrity, semantics and authority

A trusted expected digest can bind bytes. It does not establish a correct schema interpretation, admissible evidence or laboratory provenance. Similarly, agreement between implementations can preserve a shared incorrect assumption. Independent evaluation should vary inputs, interpretation and oracle, not only the executable.

`CONFIRMED` describes agreement with a submitted finding; a confirmed `FAIL` remains a negative audit finding. Preserve the Auditor verdict and the Verifier verdict as separate fields. Missing scope or insufficient evidence must not be rewritten as success.

## Qualification available to this release

The supplied summary reports 1,021 standalone and 580 comparison checks, all passing. The category totals and supplied plots agree. Raw execution records and the software build were not supplied; this release makes no new execution claim. [Validation report](VALIDATION_REPORT.md).

## Proposed independent evaluation (not yet performed)

Freeze the delivered build and contract before constructing fresh held-out cases. Include altered witnesses, unsupported claims, duplicate or missing record IDs and mismatched expected digests. Assess both agreement and rejection behavior. Preserve failures; any repair requires a successor version and a new holdout. This is an evaluation proposal, not additional completed testing.

## Reproduction boundary

Readers can reproduce the arithmetic of the published category counts from [validation_summary.json](../data/validation_summary.json). Reproducing product behavior requires a separately licensed package and its exact version, inputs and commands. The demonstration in this repository is a hand-checkable mathematical illustration, not a product execution receipt.
