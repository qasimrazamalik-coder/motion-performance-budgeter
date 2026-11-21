# Contract

## Capability
Audit animation inventories against duration, concurrency, reduced-motion and compositor-safe performance budgets.

## Input root
`findings` with fields: animation, severity, users_affected, confidence.

## Output
JSON containing `skill` and deterministic findings, ranking, mapping, plan or redaction results.

Reject malformed JSON. Do not infer authorization or fabricate evidence.
