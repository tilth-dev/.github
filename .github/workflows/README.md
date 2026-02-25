# Workflow Templates

Copy these into your repo's `.github/workflows/` directory and adapt.

## Available Templates

### `ci-node.yml` — Node.js CI
For TypeScript/JavaScript projects. Runs lint, type-check, test.

### `ci-python.yml` — Python CI  
For Python projects. Runs ruff, mypy, pytest.

### `release.yml` — Release / Deploy
Triggers on version tags. Builds, tests, deploys.

## Branch Protection Policy

All repos in tilth-dev enforce:
- `main`: requires PR + passing CI + 1 approval
- `dev`: requires passing CI

See CONTRIBUTING.md for full branch model.
