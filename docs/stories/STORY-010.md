# STORY-010 — Manage cash and bank transactions

As a financial manager, I want to manage cash and bank transactions so that I can track financial liquidity.

**Release:** r1 · Operational Accounting (weeks 5–8)
**Owner:** Financial Management Team
**Blocked by:** STORY-006

## The requirement this satisfies

- **REQ-015** (Functional, should) — The system must manage cash and bank transactions.

## How to build it

Develop cash and bank transaction management with audit logging.

## Failure paths you must handle

- Reconciliation errors
- Duplicate transactions
- Unauthorized access

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given a bank transaction, when I reconcile it, then it updates the cash records.
- [ ] Given a cash transaction, when I record it, then it updates the cash records.
- [ ] Trust: Cash and bank transactions are logged in the audit trail.

When every box above is ticked, stop and show the demo.
