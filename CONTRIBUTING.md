<!--
Copyright (c) 2024 Kibologic
Licensed under the MIT License. See LICENSE for details.
-->

# Contributing to Kibologic

Thank you for your interest in contributing to the Kibologic ecosystem!

This guide applies to **all repositories** under the [Kibologic organization](https://github.com/kibologic), including:

- [`swiss-lib`](https://github.com/kibologic/swiss-lib) — SwissJS Framework Core
- [`swite`](https://github.com/kibologic/swite) — Swiss Development Server & Build Tool
- [`swiss-erp`](https://github.com/kibologic/swiss-erp) *(coming soon)* — Alpine ERP Application
- Any other packages or apps published under the `@swissjs/*` or `@sws/*` scope

---

## Ground Rules

- Be respectful. See our [Code of Conduct](CODE_OF_CONDUCT.md).
- Commits must follow [Conventional Commits](https://www.conventionalcommits.org/): `type(scope): description`
- All code is TypeScript-first. Follow the patterns already in the codebase.
- No untested changes. We use `pnpm test` and CI pipelines.

---

## Getting Started

1. **Fork** the repo you want to contribute to.
2. **Clone** your fork locally.
3. **Install dependencies** with `pnpm install` (we use [pnpm workspaces](https://pnpm.io/workspaces)).
4. **Create a branch** from `develop` (not `main`):
   ```bash
   git checkout -b feat/your-feature-name develop
   ```

---

## Development Workflow

### Commit Messages

We use conventional commits:

```
feat(core): add reactive signal utility
fix(compiler): resolve .uix JSX transform edge case
chore(swite): update esbuild to latest
docs(swiss-lib): update README with SwissComponent examples
```

### Branching Strategy

| Branch | Purpose |
|---|---|
| `main` | Stable, released code |
| `develop` | Active development, PRs target here |
| `feat/*` | New features |
| `fix/*` | Bug fixes |
| `chore/*` | Maintenance tasks |

### Running Checks

```bash
pnpm lint          # ESLint
pnpm type-check    # TypeScript
pnpm test          # Vitest
```

---

## Pull Requests

- **Target branch**: `develop`
- **PR must**: pass all CI checks (lint, type-check, tests)
- **Documentation**: update relevant docs if you change behavior
- **Review**: a maintainer will review your PR — please respond to feedback promptly

---

## Reporting Issues

Open an issue on the appropriate repo. Please include:
- What happened
- What you expected
- Steps to reproduce
- Relevant code snippets or error messages

---

## License

By contributing, you agree your contributions will be licensed under the [MIT License](LICENSE).
