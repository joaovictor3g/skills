---
name: refactor-safe
description: Refactor code while preserving behavior and reducing risk. Use when reorganizing modules, renaming abstractions, simplifying complex code, extracting shared logic, or improving maintainability without changing product outcomes.
---

# Refactor Safe

Improve structure without breaking behavior.

## Workflow

1. Define current behavior boundaries and non-goals.
2. Add or confirm safety tests before structural changes.
3. Refactor in small, reviewable steps with passing checks.
4. Preserve public contracts unless explicitly requested otherwise.
5. Remove dead code and duplication introduced by previous structure.
6. Validate behavior parity and document any intentional deltas.

## Output

- Stepwise structural improvements.
- Preserved external behavior.
- Updated tests and migration notes if contracts changed.

