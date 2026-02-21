---
name: code-reviewer
description: Perform risk-focused code reviews that prioritize correctness, regressions, and test gaps. Use when reviewing pull requests, validating patches, auditing architectural changes, or assessing release-readiness of code modifications.
---

# Code Reviewer

Review for risk, not style preferences.

## Workflow

1. Understand intent and expected behavior changes.
2. Identify correctness bugs, edge-case failures, and regressions.
3. Check security, performance, and data-consistency risks.
4. Verify tests cover changed behavior and failure paths.
5. Report findings by severity with precise file references.
6. Note residual risks when full verification is not possible.

## Output

- Ordered findings by severity.
- Open questions and assumptions.
- Residual risk summary.

