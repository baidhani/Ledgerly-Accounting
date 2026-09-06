# STORY-001 — Set up a new company profile

As an accountant, I want to set up a new company profile so that I can start managing its accounts.

**Release:** r0 · Minimum Viable Accounting Core (weeks 1–4)
**Owner:** Accounting Team
**Blocked by:** nothing — you can start this now

## The requirement this satisfies

- **REQ-001** (Functional, must) — The system must allow users to create and configure a company profile.

## How to build it

Implement company setup form and validation logic. Log creation in audit trail.

## Failure paths you must handle

- Invalid company details
- Duplicate company name
- Missing mandatory fields

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given a new company setup request, when I enter valid company details, then the company profile is created.
- [ ] Given a new company setup request, when I enter invalid details, then I receive an error message.
- [ ] Trust: The creation of a company profile is logged in the audit trail.

When every box above is ticked, stop and show the demo.
