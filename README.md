# tilth-dev/.github

Org-wide defaults for all Tilth repositories.

## What lives here

| Path | Purpose |
|------|---------|
| `profile/README.md` | GitHub org profile page |
| `CONTRIBUTING.md` | Branch model, naming conventions, PR rules |
| `.github/PULL_REQUEST_TEMPLATE.md` | Default PR checklist |
| `.github/ISSUE_TEMPLATE/` | Bug report + feature request templates |
| `.github/workflows/ci-node.yml` | CI template for Node/TypeScript projects |
| `.github/workflows/ci-python.yml` | CI template for Python projects |

## Repo naming convention

`kebab-case`, noun-first. Examples: `clawguard`, `tilth-web`, `tilth-api`.

## Teams

| Team | Members | Default repo access |
|------|---------|-------------------|
| `agents` | AI agent accounts | Write |
| `maintainers` | Human maintainers (Michael/Mote) | Admin |

## Branch protection (all repos)

- `main` — requires PR + 1 approval + passing CI, no force pushes
- `dev` — requires passing CI

See CONTRIBUTING.md for full details.
