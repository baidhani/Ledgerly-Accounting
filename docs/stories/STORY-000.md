# STORY-000 — Build the Command Center

**As a** student running this programme, **I want** a single Command Center page that reads my plan and progress data at runtime, **so that** I (and anyone reviewing the project) can see what is being built, what it should move, and how far along it is — without trusting a stale report.

## Acceptance criteria

- Given the Command Center, when it is opened, then every tab is reachable and every card drills down one level.
- Given sample mode, when any tab is shown, then the sample data is visibly labelled as sample.
- Given the Command Center, when any tab renders, then `.colaberry/plan.json` and `.colaberry/progress.json` are both committed in this repo and every tab reads its content from them at runtime rather than from hard-coded values.
- Given the Command Center, when any tab is shown, then `.colaberry/manifest.json` is committed in this repo and every tab shows how old that data is and warns when the age exceeds a week.
- Trust — no tab shows a number, a connection or a result the project has not actually produced.

## Notes

Entry point: `index.html` at the repository root. Data source: `.colaberry/plan.json`, `.colaberry/progress.json`, `.colaberry/manifest.json`, `.colaberry/profile.json` (fetched at runtime, never inlined).
