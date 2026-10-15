# Product Overview

**QEC Evidence Auditor — Standard Mathematical V1** is a proprietary, locally operated mathematical-evidence auditing product. This repository is its documentation-only technical showcase, held in a private GitHub repository.

## Intended users and decisions

| Team | Evaluation question | Useful evidence |
|---|---|---|
| QEC software researchers | Are declared matrices and syndromes mathematically consistent? | Scoped GF(2) findings and independently checked witnesses |
| Experimental data teams | Did post-processing preserve record identity? | Explicit row/key reconciliation and ambiguity findings |
| Verification engineers | Can a second implementation reproduce a submitted conclusion? | Separate Auditor and Verifier decisions |
| Research infrastructure teams | Which assumptions remain outside an audit? | Declared contract, inputs and qualification boundaries |

The five modes are `claims`, `css`, `data`, `finite`, and `residual`. See [scope](SCIENTIFIC_SCOPE.md) and [architecture](ARCHITECTURE.md).

## Delivery and evaluation

The supplied product description specifies Python 3.10+ standard-library operation, separate programs and local offline processing. The showcase contains neither implementation nor installer; those properties have not been re-tested here. Evaluation delivery, permitted use and support are agreed separately.

The supplier reports 1,021/1,021 internal standalone checks and 580/580 comparison checks. See the [validation report](VALIDATION_REPORT.md) for provenance, breakdowns and limits. No physical decoder improvement, external certification or arbitrary-input correctness guarantee is offered.

[Evaluation and licensing](EVALUATION_AND_LICENSING.md) · [Demonstration](DEMONSTRATION.md)
