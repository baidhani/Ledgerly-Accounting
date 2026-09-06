# STORY-015 — Integrate AI for financial insights

As a financial analyst, I want AI integration for financial insights so that I can make informed decisions.

**Release:** r4 · AI Integration and Advanced Features (weeks 17–20)
**Owner:** AI Development Team
**Blocked by:** STORY-014

## The requirement this satisfies

- **REQ-020** (Functional, should) — The system must integrate AI capabilities for financial analysis and insights.
- **REQ-021** (Safety, must) — The system must ensure AI-generated analysis is advisory and does not alter authoritative records.

## How to build it

Implement AI integration for insights with advisory status and audit logging.

## Failure paths you must handle

- Incorrect AI insights
- Unclear advisory status
- Unauthorized AI access

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given financial data, when AI generates insights, then they are presented to the user.
- [ ] Given AI-generated insights, when there is uncertainty, then the system flags them for review.
- [ ] Trust: AI insights are logged with a timestamp and advisory status.

When every box above is ticked, stop and show the demo.
