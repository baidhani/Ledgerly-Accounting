# STORY-018 — Validate transactions for balanced entries

As an accountant, I want transactions to be validated for balanced debit and credit entries, so that financial integrity is maintained.

**Release:** r0 · Minimum Viable Accounting Core (weeks 1–4)
**Owner:** Accounting Team
**Blocked by:** nothing — you can start this now

## The requirement this satisfies

- **REQ-008** (Safety, must) — The system must validate transactions to ensure balanced debit and credit entries.

## How to build it

Implement validation logic in the transaction processing module to ensure debits equal credits before posting.

## Failure paths you must handle

- Transaction with unbalanced entries is accepted
- Validation logic fails to execute
- Error message is not displayed for invalid transactions

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given a transaction, when it is submitted, then it is validated for balanced debit and credit entries.
- [ ] Given a transaction with unbalanced entries, when it is submitted, then an error message is displayed.
- [ ] Trust: Given any transaction, when it is validated, then the validation result is logged.

When every box above is ticked, stop and show the demo.
