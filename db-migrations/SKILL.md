---
name: db-migrations
description: Plan and implement safe database schema and data migrations. Use when adding or changing tables, columns, constraints, indexes, backfills, or rollout steps that require rollback strategy and production safety.
---

# DB Migrations

Ship schema changes with rollback safety.

## Workflow

1. Assess data size, lock risk, and compatibility requirements.
2. Prefer expand-and-contract strategy for live systems.
3. Write reversible migrations and idempotent backfill steps.
4. Separate schema changes from large data moves when needed.
5. Add verification queries and rollback instructions.
6. Coordinate application rollout order with migration phases.

## Output

- Migration plan with phases.
- Schema and backfill scripts.
- Rollback and verification checklist.

