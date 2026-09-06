# STORY-006 — Produce basic financial statements

As an accountant, I want to produce financial statements so that I can report on the company's financial status.

**Release:** r0 · Minimum Viable Accounting Core (weeks 1–4)
**Owner:** Accounting Team
**Blocked by:** nothing — you can start this now

## The requirement this satisfies

- **REQ-006** (Functional, must) — The system must produce basic financial statements such as an income statement and balance sheet.

## How to build it

Develop logic for generating income statements and balance sheets. Ensure audit logging for statement generation.

## Failure paths you must handle

- Discrepancies in data
- Formatting errors
- Unauthorized access

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given a trial balance, when I generate financial statements, then they reflect the company's financial status.
- [ ] Given a trial balance, when there are discrepancies, then the statements highlight them.
- [ ] Trust: Financial statement generation is logged with a timestamp.

When every box above is ticked, stop and show the demo.
