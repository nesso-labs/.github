# Contributing to Nesso Labs

Thanks for your interest in contributing. This guide applies to all repositories under the **nesso-labs** organisation unless a repo provides its own `CONTRIBUTING.md`.

## Language

All source code, comments, commit messages, branch names, and PR descriptions **must be in English**. User-facing content (KB entries, marketing copy) may be in Italian when the target audience requires it.

## Getting started

1. **Open an Issue first** — describe the context, the goal, and the expected outcome before writing code. This avoids wasted effort and helps align on scope.
2. **Fork and branch** — create a feature branch from `main` (or `master` where applicable). Use descriptive branch names: `fix/login-timeout`, `feat/webhook-notifications`.
3. **Keep PRs small** — one logical change per PR. Smaller PRs get reviewed faster.

## Code standards

| Area | Convention |
|------|-----------|
| Python | Follow PEP 8. Use type hints for public functions. |
| JavaScript/TypeScript | ESLint + Prettier defaults. |
| Commits | Conventional Commits (`feat:`, `fix:`, `docs:`, `chore:`, `refactor:`). |
| Tests | Every bug fix includes a regression test. New features include unit tests. |
| Secrets | Never commit `.env`, credentials, or API keys. Use environment variables. |

## Pull request flow

1. Fill in the PR template (What / Why / How / Checklist).
2. Ensure CI passes.
3. Request a review — at least one approval is required before merge.
4. Squash-merge into the target branch.

## Reporting security issues

**Do not open a public issue.** Email [security@nessolabs.it](mailto:security@nessolabs.it) with details. See [SECURITY.md](SECURITY.md) for the full policy.

## Questions?

Open a blank issue or email [hello@nessolabs.it](mailto:hello@nessolabs.it).
