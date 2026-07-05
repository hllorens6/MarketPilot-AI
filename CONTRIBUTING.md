# Contributing to MarketPilot AI

Version: 0.1.0
Status: Draft

## Purpose

This document defines how changes should be proposed, reviewed, and merged into MarketPilot AI.

## Development Philosophy

Every change should support one of these goals:

- Improve decision quality
- Improve explainability
- Improve risk management
- Improve reliability
- Improve user workflow

## Branching Model

- `main` contains stable project releases.
- Feature and release work should happen in branches.
- Pull Requests should be reviewed before merging into `main`.

Recommended branch format:

```text
release/v0.1.0-foundation
feature/opportunity-score
feature/telegram-alerts
fix/readme-links
```

## Pull Request Expectations

Every Pull Request should include:

- Summary of changes
- Why the change matters
- Files changed
- Risk or limitations
- Next steps

## Documentation First

For major features, documentation should come before implementation.

## Review Checklist

Before merging, verify:

- The change has a clear purpose.
- The change supports MarketPilot AI principles.
- Risk implications are documented.
- Naming is consistent.
- The project remains simple and understandable.

## Current Roles

- Product Owner: hllorens6
- Lead Architect: Atlas design assistant

## Motto

Decisions backed by data. Executed with discipline.
