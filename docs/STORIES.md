# Intelligent Accounting and Business Management System — Stories

20 stories across 5 releases, walking-skeleton first:
the earliest release proves the thinnest end-to-end path including the trust
spine, and later releases stack features on top of something already working.

## Before the releases — start here

- **[STORY-000](stories/STORY-000.md)** — Build your Command Center

The first thing you build, on day one, before any part of the system itself. It is
the page you keep open for the rest of the programme and demo from. It belongs to no
release and fulfils none of your requirements, because it is the window onto your
system rather than a part of it.

## r0 · Minimum Viable Accounting Core — weeks 1–4

**Goal:** Establish a functional accounting core with integrity and auditability.
**Done when you can show:** Demonstrate end-to-end accounting workflow with audit trails and integrity checks.

- **[STORY-001](stories/STORY-001.md)** — Set up a new company profile
- **[STORY-002](stories/STORY-002.md)** — Create and maintain chart of accounts
- **[STORY-003](stories/STORY-003.md)** — Create manual journal entries
- **[STORY-004](stories/STORY-004.md)** — Post transactions to the general ledger
- **[STORY-006](stories/STORY-006.md)** — Produce basic financial statements
- **[STORY-017](stories/STORY-017.md)** — Implement audit trails for financial transactions
- **[STORY-018](stories/STORY-018.md)** — Validate transactions for balanced entries
- **[STORY-019](stories/STORY-019.md)** — Handle invalid accounting data with error messages

## r1 · Operational Accounting — weeks 5–8

**Goal:** Expand to include operational accounting features like AR/AP, sales, and expenses.
**Done when you can show:** Show integration of sales and expenses with the accounting core.

- **[STORY-005](stories/STORY-005.md)** — Generate a trial balance _(waits on STORY-004)_
- **[STORY-007](stories/STORY-007.md)** — Manage customer and vendor profiles _(waits on STORY-006)_
- **[STORY-008](stories/STORY-008.md)** — Manage accounts receivable and payable _(waits on STORY-006)_
- **[STORY-009](stories/STORY-009.md)** — Handle sales, purchasing, and expenses _(waits on STORY-006)_
- **[STORY-010](stories/STORY-010.md)** — Manage cash and bank transactions _(waits on STORY-006)_
- **[STORY-020](stories/STORY-020.md)** — Import and export data via Excel/CSV _(waits on STORY-010)_

## r2 · Financial Management — weeks 9–12

**Goal:** Introduce budgeting, cost centers, and enhanced financial reporting.
**Done when you can show:** Demonstrate budgeting and cost center management with financial reports.

- **[STORY-011](stories/STORY-011.md)** — Implement budgeting and cost centers _(waits on STORY-010)_
- **[STORY-012](stories/STORY-012.md)** — Enhance financial reporting capabilities _(waits on STORY-010)_

## r3 · Scalability and User Management — weeks 13–16

**Goal:** Support multi-company operations and advanced user roles.
**Done when you can show:** Show multi-company setup and role-based access control.

- **[STORY-013](stories/STORY-013.md)** — Support multi-company operations _(waits on STORY-012)_
- **[STORY-014](stories/STORY-014.md)** — Implement advanced user roles and permissions _(waits on STORY-012)_

## r4 · AI Integration and Advanced Features — weeks 17–20

**Goal:** Integrate AI for financial insights and prepare for future expansions.
**Done when you can show:** Demonstrate AI-driven financial analysis and insights.

- **[STORY-015](stories/STORY-015.md)** — Integrate AI for financial insights _(waits on STORY-014)_
- **[STORY-016](stories/STORY-016.md)** — Prepare system for future integrations _(waits on STORY-014)_
