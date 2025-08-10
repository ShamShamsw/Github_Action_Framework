# GitHub Actions Basic Demo

This repository demonstrates a basic workflow using GitHub Actions for Continuous Integration (CI) with Python.

## Structure

- `src/` — Source code for the application.
- `tests/` — Unit tests for the application.
- `.github/workflows/ci.yml` — GitHub Actions workflow configuration.
- `CHANGELOG.md` — Update log for the project.

## How It Works

- On every push or pull request to the `main` branch, the CI workflow runs:
  - Checks out the code
  - Installs dependencies
  - Runs unit tests with `pytest`

## Running Locally

1. Install Python 3.11+
2. Install dependencies: `pip install pytest`
3. Run tests: `pytest tests/`

## GitHub Actions Workflow

The workflow is defined in `.github/workflows/ci.yml` and will run automatically in GitHub.

## License

MIT
