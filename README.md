# Library Data Pipeline

![Teaching](https://img.shields.io/badge/module-DE5M6-blue)
![Python Version](https://img.shields.io/badge/python-3.9--3.12-blue.svg)

![Open Issues](https://img.shields.io/github/issues/YOUR_USERNAME/YOUR_REPO)
![Open PRs](https://img.shields.io/github/issues-pr/YOUR_USERNAME/YOUR_REPO)
![Last Commit](https://img.shields.io/github/last-commit/YOUR_USERNAME/YOUR_REPO)
![CI Pipeline Badge](https://github.com/YOUR_USERNAME/YOUR_REPO/actions/workflows/ci.yml/badge.svg)

*Replace `YOUR_USERNAME/YOUR_REPO` with your details*

## Project Overview
[TODO: Describe the library's data quality problem]

## Architecture
[TODO: Add architecture diagram]

See [docs/architecture/](docs/architecture/) for details.

## Setup

### Git

At a prompt copy and paste the following 2 lines:

```sh
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

### Local Development
```bash
# Clone this repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

# Create virtual environment
python -m venv venv
.\venv\Scripts\Activate.ps1

# Confirm the Python 3 version
python --version

# Install dependencies
pip install -r requirements.txt

# Run tests
pytest tests/ -v

# Run Python tests with a HTML coverage report
pytest tests/ -v --cov=src --cov-report=html
```

## Project Structure
[TODO: Document your folder structure]

## Data Sources
[TODO: Describe the data files]

## Testing
[TODO: Document your testing approach]

Current coverage: [TODO: Add coverage badge]

## CI/CD
This project uses GitHub Actions for continuous integration.

See [.github/workflows/ci.yml](.github/workflows/ci.yml)

## Deployment to Fabric
[TODO: Document Fabric deployment process]

## Team
[TODO: Add team members]
