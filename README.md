# Skills

This directory contains reusable skills for coding workflows.

## What a Skill Is

A skill is a folder with instructions that guide the agent for a specific type of work.

Required file:
- `SKILL.md`

Common optional files:
- `agents/openai.yaml`
- `scripts/`
- `references/`
- `assets/`

## How Skills Are Used

- Codex: invoke with `$skill-name`.
- Other agents: start prompts with `Skill: skill-name` and load the matching playbook.

## Available Skills

- `api-contracts`: Define and enforce API contracts.
- `bug-triage`: Reproduce bugs and deliver verified fixes.
- `ci-cd-maintainer`: Improve CI/CD reliability and speed.
- `code-reviewer`: Review code for correctness and regression risk.
- `db-migrations`: Plan safe schema and data migrations.
- `desing-interface`: Build UI-only interfaces and interaction states.
- `docs-from-code`: Generate docs from real implementation behavior.
- `observability-setup`: Add logs, metrics, tracing, and alerts.
- `performance-profiler`: Measure bottlenecks and optimize performance.
- `refactor-safe`: Refactor while preserving behavior.
- `release-prep`: Prepare release gates, rollout, and rollback.
- `security-hardening`: Strengthen auth, input handling, and secrets safety.
- `seo-quality`: Improve and verify technical and on-page SEO.
- `test-writer`: Add reliable tests for changed behavior.
- `ux-ui`: Improve usability, accessibility, and visual hierarchy.

## Authoring Guidelines

- Keep `name` and `description` in `SKILL.md` frontmatter accurate.
- Keep instructions concise and action-oriented.
- Prefer reusable workflows over project-specific details.
- Add scripts/references only when they reduce repeated work.

## Maintenance

- Treat each skill's `SKILL.md` as the source of truth.
- Regenerate cross-agent playbooks after skill updates.
