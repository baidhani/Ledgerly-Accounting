# STORY-002 — Create and maintain chart of accounts

As an accountant, I want to create and maintain a chart of accounts so that I can organize financial transactions.

**Release:** r0 · Minimum Viable Accounting Core (weeks 1–4)
**Owner:** Accounting Team
**Blocked by:** nothing — you can start this now

## The requirement this satisfies

- **REQ-002** (Functional, must) — The system must support the creation and maintenance of a chart of accounts.

## How to build it

Develop UI for chart of accounts management. Ensure audit logging for changes.

## Failure paths you must handle

- Invalid account data
- Duplicate account code
- Unauthorized access

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given a chart of accounts setup, when I add a new account, then it appears in the chart.
- [ ] Given a chart of accounts setup, when I add an account with invalid data, then I receive an error message.
- [ ] Trust: Changes to the chart of accounts are logged in the audit trail.

When every box above is ticked, stop and show the demo.
