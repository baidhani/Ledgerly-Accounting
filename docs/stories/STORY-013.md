# STORY-013 — Support multi-company operations

As a system administrator, I want to support multi-company operations so that I can manage multiple entities.

**Release:** r3 · Scalability and User Management (weeks 13–16)
**Owner:** System Administration Team
**Blocked by:** STORY-012

## The requirement this satisfies

- **REQ-018** (Functional, should) — The system must support multi-company and multi-branch operations.

## How to build it

Implement multi-company support with context switching and audit logging.

## Failure paths you must handle

- Context switch errors
- Unauthorized access
- Data consolidation errors

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given multiple companies, when I switch contexts, then the system reflects the selected company.
- [ ] Given multiple companies, when I consolidate reports, then it includes all selected entities.
- [ ] Trust: Company context switches are logged in the audit trail.

When every box above is ticked, stop and show the demo.
