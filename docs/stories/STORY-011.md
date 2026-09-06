# STORY-011 — Implement budgeting and cost centers

As a financial manager, I want to implement budgeting and cost centers so that I can control financial planning.

**Release:** r2 · Financial Management (weeks 9–12)
**Owner:** Financial Management Team
**Blocked by:** STORY-010

## The requirement this satisfies

- **REQ-017** (Functional, should) — The system must support budgeting and cost centers.

## How to build it

Develop budgeting and cost center management with audit logging.

## Failure paths you must handle

- Budget allocation errors
- Unauthorized budget changes
- Duplicate cost centers

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given a budget, when I allocate funds, then it updates the cost center records.
- [ ] Given a cost center, when I adjust its budget, then it reflects in financial reports.
- [ ] Trust: Budget and cost center changes are logged in the audit trail.

When every box above is ticked, stop and show the demo.
