# STORY-007 — Manage customer and vendor profiles

As a business manager, I want to manage customer and vendor profiles so that I can track business relationships.

**Release:** r1 · Operational Accounting (weeks 5–8)
**Owner:** Business Management Team
**Blocked by:** STORY-006

## The requirement this satisfies

- **REQ-012** (Functional, should) — The system must support customer and vendor management.

## How to build it

Implement customer and vendor profile management with audit logging.

## Failure paths you must handle

- Invalid profile data
- Unauthorized deletion
- Duplicate profiles

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given a customer profile, when I update details, then the changes are saved.
- [ ] Given a vendor profile, when I delete it, then it is removed from the system.
- [ ] Trust: Changes to profiles are logged in the audit trail.

When every box above is ticked, stop and show the demo.
