# STORY-020 — Import and export data via Excel/CSV

As a data analyst, I want to import and export data via Excel/CSV, so that I can easily manage and share data.

**Release:** r1 · Operational Accounting (weeks 5–8)
**Owner:** Data Management Team
**Blocked by:** STORY-010

## The requirement this satisfies

- **REQ-011** (Functional, must) — The system must allow for the import and export of data via Excel/CSV.

## How to build it

Implement import/export functionality using existing libraries for Excel/CSV handling and ensure logging of all operations.

## Failure paths you must handle

- Exported file format is incorrect
- Import fails to correctly parse data
- Logging fails for import/export operations

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given a dataset, when it is exported, then it is available in Excel/CSV format.
- [ ] Given an Excel/CSV file, when it is imported, then the data is correctly added to the system.
- [ ] Trust: Given any data import/export, when it is completed, then the action is logged with a timestamp.

When every box above is ticked, stop and show the demo.
