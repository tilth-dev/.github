# Contributing to Tilth

## Branch Model

| Branch | Purpose | Protected |
|--------|---------|-----------|
| `main` | Stable, deployable | ✅ Yes |
| `dev` | Integration branch | ✅ Yes |
| `feature/*` | New work | No |
| `fix/*` | Bug fixes | No |
| `chore/*` | Non-functional changes | No |

## Pull Request Rules

1. All PRs target `dev` (not `main` directly)
2. PRs require at least one approval
3. CI must pass — no exceptions
4. PRs must include a test or explain why none is needed

## Commit Style

```
type(scope): short description

types: feat | fix | chore | docs | test | ci | refactor
scope: component or module name
```

## Naming Conventions

| Thing | Convention | Example |
|-------|-----------|---------|
| Repos | `kebab-case`, noun-first | `clawguard`, `tilth-web` |
| Branches | `type/short-description` | `feature/manifest-check` |
| Services | Same as repo name | `clawguard` |

## Code Quality Bar

- Tests must cover critical paths
- No hardcoded secrets (env vars only)
- Every service: run command, health check, stop command documented
- Changes must be incremental and reversible

Full standards: see `venture-company/standards/`
