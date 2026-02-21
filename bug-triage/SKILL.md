---
name: bug-triage
description: Reproduce, isolate, and fix software defects with minimal risk. Use when users report bugs, regressions, flaky behavior, runtime errors, failed builds, or unexpected outputs that require root-cause analysis and a verified patch.
---

# Bug Triage

Resolve defects quickly and safely.

## Workflow

1. Capture exact symptom, environment, expected behavior, and actual behavior.
2. Reproduce the issue with deterministic steps before changing code.
3. Isolate the failing layer and identify root cause, not just symptoms.
4. Implement the smallest safe fix that restores expected behavior.
5. Add or update a regression test that fails before and passes after the fix.
6. Verify with relevant checks and summarize impact, risk, and follow-up items.

## Output

- Reproduction steps.
- Root-cause statement.
- Minimal patch.
- Regression test coverage.
- Verification results.

