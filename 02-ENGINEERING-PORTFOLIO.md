# Engineering Portfolio and Architecture Index

This file is the index for substantial projects. Detailed architecture documents belong beside the relevant project under `projects/`.

## Project quality bar

Every substantial project should document:

1. Problem, users, goals, and non-goals.
2. Requirements and constraints.
3. Architecture diagram and component responsibilities.
4. Data flow, network flow, identity, and trust boundaries.
5. Infrastructure and application implementation.
6. Configuration and secrets strategy (never commit secret values).
7. CI/CD, testing, and release/rollback process.
8. Observability: logs, metrics, traces, alerts, and dashboards as appropriate.
9. Reliability: health checks, backups, recovery, capacity, and failure behavior.
10. Security review and threat considerations.
11. Cost and operational trade-offs.
12. Reproduction steps, runbooks, evidence, and lessons learned.

## Portfolio register

| Project | Status | Main skills | Evidence |
|---|---|---|---|
| Not started | Planned | To be determined after baseline | |

## Architecture decision records

Use [the decision log](05-DECISION-LOG.md) for significant decisions. Each record should capture context, options, decision, consequences, and revisit conditions.

## Project status definitions

- Planned
- In progress
- Blocked
- Review required
- Completed with evidence
- Archived

A project is not complete merely because it deploys once. It must be reproducible, tested, documented, and have its operational limitations explained.
