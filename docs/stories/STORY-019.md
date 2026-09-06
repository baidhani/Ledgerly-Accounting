# STORY-019 — Handle invalid accounting data with error messages

As a user, I want the system to handle invalid accounting data and provide understandable error messages, so that I can correct issues promptly.

**Release:** r0 · Minimum Viable Accounting Core (weeks 1–4)
**Owner:** User Experience Team
**Blocked by:** nothing — you can start this now

## The requirement this satisfies

- **REQ-009** (Safety, must) — The system must handle invalid accounting data and provide understandable error messages.

## How to build it

Ensure all data entry points include validation checks and error handling to provide user feedback.

## Failure paths you must handle

- Invalid data is accepted without error
- Error message is unclear or not displayed
- Error logging fails for invalid data entries

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given invalid accounting data, when it is entered, then an error message is displayed to the user.
- [ ] Given valid accounting data, when it is entered, then it is accepted without error.
- [ ] Trust: Given any invalid data entry, when it is processed, then the error is logged with details.

When every box above is ticked, stop and show the demo.
