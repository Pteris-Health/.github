# Contributing

**English** · [Русский](CONTRIBUTING.ru.md)

These guidelines apply to every repository in the Pteris Health organization
unless a repository overrides them.

## Workflow

1. Branch from `main` using a prefix: `feat/`, `fix/`, `chore/`, `docs/`,
   `refactor/`, `test/`, `perf/`, `ci/`.
2. Keep pull requests focused on one logical change.
3. Add or update tests for any behavior change.
4. Make sure the check suite passes locally before pushing.
5. Open a pull request against `main` and fill in the template.

## Commit messages

Use [Conventional Commits](https://www.conventionalcommits.org/):

```text
<type>(<optional scope>): <short summary>
```

## Pull requests

- Link the issue the pull request closes (`Closes #123`).
- All checks must pass and review conversations must be resolved.
- Squash merge only. The pull request title becomes the commit subject.
- Commits must be signed (`git config --global commit.gpgsign true`).
- At least one approving review is required.

## Security

Do not open public issues for security problems. See [SECURITY.md](SECURITY.md).
