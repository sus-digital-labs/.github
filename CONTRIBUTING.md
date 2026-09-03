# Contributing to SUS Digital Labs

## Welcome
Thank you for your interest in contributing to SUS Digital Labs! We are an independent open-source initiative focused on digital health and public-health engineering in Brazil.

## Before contributing
Please read our [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) and [SECURITY.md](SECURITY.md).

## Find an issue
Check the issue tracker for `good first issue` or `help wanted` labels. If you want to work on a new feature, please open a feature request or discussion first to ensure alignment.

## Development setup
Each repository contains specific setup instructions in its own `README.md`.

## Branch naming
Use descriptive branch names:
- `feat/` for new features
- `fix/` for bug fixes
- `docs/` for documentation
- `test/` for testing
- `refactor/` for refactoring
- `perf/` for performance improvements
- `ci/` for CI/CD changes
- `chore/` for maintenance

## Commit messages
We follow [Conventional Commits](https://www.conventionalcommits.org/):
- `feat(sync): support incremental patient export`
- `fix(auth): prevent expired session reuse`
- `docs(api): document ingestion contract`

## Pull requests
- Keep PRs small and focused on a single issue.
- Do not mix refactoring with new features.
- Include automated tests for new behaviors.
- Do not alter global formatters unintentionally.
- Document any breaking changes.

## Security and sensitive data
**CRITICAL:** NEVER publish real patient data, credentials, connection strings, or sensitive infrastructure information in Issues, PRs, logs, or commits.
Fixtures must be strictly synthetic, anonymized, and generated (e.g., `EXAMPLE MUNICIPALITY`, `Paciente Teste S-1`).

## Code review
Maintainers will review your PR. Please be responsive to feedback.

## Licensing
By contributing, you agree that your contributions will be licensed under the project's open-source license.
