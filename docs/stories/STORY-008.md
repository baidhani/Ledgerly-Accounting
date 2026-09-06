# STORY-008 — Manage accounts receivable and payable

As a financial manager, I want to manage accounts receivable and payable so that I can ensure timely payments.

**Release:** r1 · Operational Accounting (weeks 5–8)
**Owner:** Financial Management Team
**Blocked by:** STORY-006

## The requirement this satisfies

- **REQ-013** (Functional, should) — The system must manage accounts receivable and payable.

## How to build it

Develop AR/AP management features with audit logging for payment actions.

## Failure paths you must handle

- Duplicate payments
- Incorrect invoice data
- Unauthorized payment actions

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given an invoice, when I mark it as paid, then it updates the accounts receivable.
- [ ] Given a bill, when I mark it as paid, then it updates the accounts payable.
- [ ] Trust: Payment actions are logged in the audit trail.

When every box above is ticked, stop and show the demo.
