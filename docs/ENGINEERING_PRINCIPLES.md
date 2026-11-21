# Workflow Engine: Engineering principles

These are intended product engineering constraints, not evidence of implemented features.

## Reusable and deterministic core

- Keep industry-specific rules outside the core execution engine.
- Represent execution prerequisites and branch outcomes explicitly.
- Use reproducible inputs, including an explicit clock and deterministic tie-breaking.
- Validate malformed definitions and illegal state transitions.

## Human control

- Actions requiring approval must not execute without valid authority.
- Approval revocation, retry and restart must not create an authorization bypass.
- Operator decisions and action outcomes must be attributable and auditable.

## Durable and safe execution

- Persist meaningful execution state across interruptions.
- Treat confirmed execution, authoritative non-execution and uncertain outcome as distinct conditions.
- Do not retry an uncertain external side effect automatically.
- A stable action identifier alone does not guarantee exactly-once acceptance. Any duplicate-prevention claim depends on the receiving system's documented idempotency or reconciliation guarantees.

## Verification

- Test normal, invalid, boundary and failure behavior.
- Include crash and concurrency scenarios where relevant.
- Review actual results, not completion claims alone.
- Use only synthetic records and simulated external actions during initial development.

Implementation choices and test details will evolve as the project develops.
