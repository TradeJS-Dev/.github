# Contributing to TradeJS

Thanks for considering a contribution.

## Before You Start

- Use `TradeJS` for framework, app, packages, CLI, runtime, and infra changes.
- Use `TradeJS-Docs` for public documentation changes.
- Use `TradeJS-Site` for public marketing site changes.
- Start with an issue or discussion before large features, breaking changes, or architecture changes.

## Contribution Expectations

- Keep changes focused and avoid unrelated formatting churn.
- Match the existing package boundaries and public API policy.
- Prefer fixing root causes over adding temporary workarounds.
- Document user-visible behavior changes.
- Add or update tests when behavior changes.

## Pull Requests

Good pull requests usually include:

- a clear problem statement
- a concise summary of the approach
- validation steps
- screenshots for UI changes
- migration notes for breaking changes

Before opening a PR, run the relevant checks when practical:

- `yarn lint`
- `yarn typecheck`
- `yarn unit`
- package-local or app-local checks for the area you changed

## Issues

Please use issue templates where available.

- Use bug reports for broken behavior or regressions.
- Use feature requests for substantial improvements.
- Use docs issues for documentation clarity, accuracy, or missing coverage.

For questions and design discussion, prefer GitHub Discussions when available.

## Security

Do not report security vulnerabilities in public issues.

Use the repository security process described in `SECURITY.md`.
