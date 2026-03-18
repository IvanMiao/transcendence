# Contributing Guidelines

## Branches

- **NEVER push directly to `main`.** All changes must go through a pull request.
- Each branch covers **one feature or fix only**.
- Name branches with a prefix: `feat/`, `fix/`, `docs/`, `refactor/`, `chore/`, `test/`
	- **Example:** `feat/user-auth`, `fix/login-crash`

## Commits

- Keep commits **atomic** — one logical change per commit.
- Use [Conventional Commits](https://www.conventionalcommits.org/) format: `<type>: <short description>`
  - Common types: `feat`, `fix`, `docs`, `refactor`, `chore`, `test`
- Write in the **imperative mood**, under **72 characters**.

## Pull Requests

- Every PR requires **at least one approval** before merging.
- The PR description should briefly state **what** changed and **why**.
- Reference related issues where applicable (e.g. `closes #42`).

## Security

- Never commit secrets, credentials, `.env` files, or API keys.
- If a secret is accidentally committed, treat it as compromised immediately.
