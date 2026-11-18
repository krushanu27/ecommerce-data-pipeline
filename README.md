# Ecommerce Data Pipeline

## Overview

A modular Python-based data engineering project designed to ingest, transform, validate, and load ecommerce data.

The project aims to establish a structured ETL pipeline with database integration and data quality controls.

## Technology Stack

- Python 3.12
- Pandas
- NumPy
- SQLAlchemy
- PyODBC
- Microsoft SQL Server
- Git

## Project Architecture

```text
config/
data/
    raw/
    processed/
    external/
notebooks/
sql/
src/
    ingestion/
    transformation/
    validation/
    loading/
    utils/
tests/
docs/
logs/
```

## Development Environment

- Operating System: Ubuntu 24.04 (WSL2)
- Python Environment: `.venv`
- Version Control: Git

## Setup

Clone the repository and create a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Project Status

Initial development environment and project structure established.

## License

To be determined.