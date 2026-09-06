# STORY-003 — Create manual journal entries

As an accountant, I want to create manual journal entries so that I can record financial transactions accurately.

**Release:** r0 · Minimum Viable Accounting Core (weeks 1–4)
**Owner:** Accounting Team
**Blocked by:** nothing — you can start this now

## The requirement this satisfies

- **REQ-003** (Functional, must) — The system must allow users to create manual journal entries following debit and credit rules.

## How to build it

Implement journal entry form with validation for balanced entries. Log entries in audit trail.

## Failure paths you must handle

- Unbalanced entries
- Invalid account codes
- Unauthorized user

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given a journal entry form, when I enter valid debit and credit entries, then the entry is saved.
- [ ] Given a journal entry form, when I enter unbalanced entries, then I receive an error message.
- [ ] Trust: Journal entries are logged with a timestamp and user ID.

When every box above is ticked, stop and show the demo.
