# STORY-009 — Handle sales, purchasing, and expenses

As a business manager, I want to handle sales, purchasing, and expenses so that I can manage business operations.

**Release:** r1 · Operational Accounting (weeks 5–8)
**Owner:** Business Management Team
**Blocked by:** STORY-006

## The requirement this satisfies

- **REQ-014** (Functional, should) — The system must handle sales, purchasing, and expenses.

## How to build it

Implement sales and purchasing processing with audit logging.

## Failure paths you must handle

- Invalid order data
- Duplicate orders
- Unauthorized processing

## Acceptance — your stop condition

Tick each box as it genuinely passes. This file is yours — the platform reads
the same criteria out of `.colaberry/progress.json`, which Claude Code keeps in
step (see the managed block in CLAUDE.md). Ticking something you have not
actually met only misleads you.

- [ ] Given a sales order, when I process it, then it updates the sales records.
- [ ] Given a purchase order, when I process it, then it updates the purchasing records.
- [ ] Trust: Sales and purchasing actions are logged in the audit trail.

When every box above is ticked, stop and show the demo.
