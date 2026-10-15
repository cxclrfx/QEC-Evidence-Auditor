# Demonstration and Evaluation Guide

## Documentation-only demonstration

This release contains no runnable Auditor or Verifier. The example below is an illustrative conventional-mathematics exercise, not a captured product run or a claim that these values constitute an accepted product input schema.

Take the binary rows Hx = [1, 1, 0] and Hz = [1, 1, 1]. Their dot product is 1 + 1 + 0 = 0 modulo 2, so this pair passes the stated commutation check. Changing Hz to [1, 0, 1] gives 1 modulo 2 and fails that check. A separate verification calculation should re-evaluate the same declared rows rather than trust a PASS label.

This example proves only the stated row-pair calculation. It establishes neither code distance nor logical error suppression. The two illustrative cases are not added to the historical 1,021 or 580 counts.

## Suggested licensed demonstration

1. Agree on the permitted dataset, supported mode, exact product version and acceptance criteria.
2. Obtain the owner-approved evaluation package and trusted digests under a separate agreement.
3. Follow the package's actual instructions; no unverified command syntax is supplied here.
4. Run Auditor locally to a fresh output location, then run Verifier with the original declared input and generated evidence.
5. Keep both decisions and execution receipts. Demonstrate a valid case and an authorized tampered-evidence case.
6. Record limitations, rejected or unsupported input, and any NOT_RUN cases explicitly.

## Access and terms

Authorized collaborators can raise a non-confidential inquiry in the private repository. Other parties need an owner-approved contact route. Evaluation duration, license scope, support, data handling, acceptance criteria and pricing require a written agreement; no free-use or redistribution right is implied.

[Licensing](EVALUATION_AND_LICENSING.md) · [Scope](SCIENTIFIC_SCOPE.md)
