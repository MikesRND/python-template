# Python Repository Template

Template repository, defines a simple package called my-package

## Development

### Create a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
```

### Install package

```bash
pip install -e .[dev]
```

## Run all code tests and checks

```bash
pre-commit run --all-files
```

## Run Tests

```bash
pytest
```

Run with coverage:

```bash
pytest --cov=.
```

## Build Docs
```bash
mkdocs serve
```

## Run Lint

```bash
ruff check .
```

## Type Checking

```bash
mypy .
```


## Report test coverage

```bash
coverage run -m pytest
coverage report
```
