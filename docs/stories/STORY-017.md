# STORY-017 — Implement audit trails for financial transactions

As a compliance officer, I want audit trails for all financial transactions, so that I can ensure accountability and traceability.

**Release:** r0 · Minimum Viable Accounting Core (weeks 1–4)
**Owner:** Compliance Team
**Blocked by:** nothing — you can start this now

## The requirement this satisfies

- **REQ-007** (Safety, must) — The system must provide audit trails for all financial transactions and changes.

## How to build it

Implement audit trail logging for all transaction endpoints and ensure entries are stored in the audit_logs table.

## Failure paths you must handle

- Audit trail entry not created on transaction completion
- Audit trail entry not updated on transaction modification
- Audit trail data is incomplete or missing timestamps

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given a financial transaction, when it is completed, then an audit trail entry is created.
- [ ] Given a change to a financial transaction, when it is modified, then an audit trail entry is updated.
- [ ] Trust: Given any financial transaction, when it is audited, then the audit trail shows all changes and timestamps.

When every box above is ticked, stop and show the demo.
