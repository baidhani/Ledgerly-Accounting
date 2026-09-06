# STORY-004 — Post transactions to the general ledger

As an accountant, I want to post transactions to the general ledger so that they are reflected in financial reports.

**Release:** r0 · Minimum Viable Accounting Core (weeks 1–4)
**Owner:** Accounting Team
**Blocked by:** nothing — you can start this now

## The requirement this satisfies

- **REQ-004** (Functional, must) — The system must post transactions to the general ledger and maintain accounting integrity.

## How to build it

Develop logic for posting entries to the general ledger. Ensure audit logging for posting actions.

## Failure paths you must handle

- Unbalanced entries
- Duplicate postings
- System errors during posting

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given a set of journal entries, when I post them, then they appear in the general ledger.
- [ ] Given a set of journal entries, when I post unbalanced entries, then the system prevents posting.
- [ ] Trust: Posting actions are recorded in the audit trail.

When every box above is ticked, stop and show the demo.
