# Technical Validation Report — Standard Mathematical V1

**Report date:** 15 October 2026. **Qualification:** Internal evaluation, not external certification.

## Evidence provenance

The source showcase archive supplies this summary and its plots, not raw test logs, test code, seeds, executable artifacts or a frozen product-build digest. Totals and plot labels have been checked for consistency. Product tests were **NOT_RUN** during showcase preparation. Independent closure of the reported execution history is **NOT_ESTABLISHED**. The two suites are reported separately; their sizes do not establish statistical independence.

## Executive summary

| Category | Passed | Failed |
|---|---:|---:|
| Standalone synthetic tests | **1,021** | 0 |
| Mathematical regression/comparison checks | **580** | 0 |

These figures are counts of recorded successful checks. They are not an error-rate estimate for untested data or a comparison against commercial QEC products.

## Standalone test breakdown

| Internal test category | Checks |
|---|---:|
| `css_oracle` | 280 |
| `css_tamper` | 40 |
| `data_oracle` | 100 |
| `data_tamper` | 25 |
| `finite_random` | 180 |
| `finite_tamper` | 40 |
| `modular_oracle` | 280 |
| `modular_tamper` | 40 |
| `claim_scenarios` | 14 |
| `claim_tamper` | 2 |
| `cli_auditor` | 5 |
| `cli_verifier` | 5 |
| `cli_no_overwrite` | 5 |
| `cli_wrong_hash` | 5 |
| **TOTAL** | **1,021** |

![Test distribution](../assets/test_coverage.png)

## Regression/comparison breakdown

| Comparison category | Checks |
|---|---:|
| `css` | 30 |
| `data` | 7 |
| `finite` | 40 |
| `residual` | 60 |
| `claims` | 1 |
| `mutation` | 12 |
| `finite_random` | 180 |
| `residual_random` | 250 |
| **TOTAL** | **580** |

![Comparison distribution](../assets/comparison_summary.png)

## Qualification limits

The underlying release tests and the frozen prior-program comparison were conducted within the same research line. An external organization did not independently administer the test program.

The technical showcase intentionally does **not** distribute the private source inputs or archived research material used in the regression comparison. These numerical summaries therefore support transparency about reported local testing, not third-party reproducibility of the complete test history.

## Release status

Supplier-reported product status: `READY_FOR_LOCAL_EVALUATION`. This documentation release does not independently qualify a delivered software build.

Hardware authority: **not established**. External blind examination: **not performed**. Behavioural equivalence on all possible legal inputs: **not formally proven**.
