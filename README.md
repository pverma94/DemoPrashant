# GitHub Actions Project – Prashant Verma

This project demonstrates the setup and execution of a GitHub Actions workflow triggered by changes committed to the `app.py` file.

## Purpose

The main goal is to automate tasks such as code checkout, Python setup, and linting using GitHub Actions. This helps maintain code quality and streamlines development processes.

## Workflow Highlights

- Automatically runs when code is pushed to the `main` branch
- Uses `flake8` to check code quality and detect potential issues
- Logs and status are available under the **Actions** tab on GitHub

## Files Included

- `app.py`: Sample Python script
- `.github/workflows/prashant.yaml`: GitHub Actions configuration file
- `README.md`: Project description

## How It Works

1. Any changes pushed to the repository trigger the workflow.
2. GitHub Actions runs a series of steps defined in `prashant.yaml`.
3. The workflow installs dependencies and performs linting.
4. Results are displayed in the Actions tab.
