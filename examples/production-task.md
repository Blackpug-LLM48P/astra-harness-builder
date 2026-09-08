# Production Task Example

## Objective

Diagnose an elevated error rate in a named production service and propose a reversible remediation.

## Boundaries

- Begin with read-only inspection.
- Touch only the named service and observability sources.
- Do not deploy, restart, scale, or change configuration without approval.
- Do not expose credentials, customer data, or private logs.

## Acceptance criteria

- Evidence-backed cause or a clearly stated uncertainty set.
- Impact assessment.
- Reversible remediation plan.
- Verification and rollback steps.
- Explicit approval request immediately before any production mutation.
