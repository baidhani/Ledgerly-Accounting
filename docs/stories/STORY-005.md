# STORY-005 — Generate a trial balance

As an accountant, I want to generate a trial balance, so that I can verify the accuracy of the ledger.

**Release:** r1 · Operational Accounting (weeks 5–8)
**Owner:** Accounting Team
**Blocked by:** STORY-004

## The requirement this satisfies

- **REQ-005** (Functional, must) — The system must generate a trial balance from posted transactions.

## How to build it

Implement the trial balance generation using the existing ledger data structure. Ensure that the output is formatted correctly and includes all necessary account information.

## Failure paths you must handle

- Ledger data is incomplete
- Ledger data is corrupted
- User lacks permissions
- System timeout
- Data format mismatch

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given a set of ledger entries, when I generate a trial balance, then it should display all accounts with their balances.
- [ ] Given an unbalanced ledger, when I attempt to generate a trial balance, then it should indicate an error.
- [ ] Trust: The generation of a trial balance must be logged with the user ID and timestamp.

When every box above is ticked, stop and show the demo.
