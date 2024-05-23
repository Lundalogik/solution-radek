# radek

[//]: # (Please fill in content about this module.)

## What this package does

[//]: # (Please fill in content about what this module does.)

## Developing

### Setting up your environment with Poetry

[Install Poetry](https://python-poetry.org/docs/#installation)

## Installing dependencies

### Creating lock file

```bash
poetry lock
```

### Installing from lock file

```bash
poetry install
```

## Running tests

```bash
pytest
```

## Configuration

To add default configuration options to this package, add them to solution-radek/solution_radek/__init__.py like so:

```python
def default_config():
    return {
        'my-option': 'its default value'
    }
```

These options can later be retrieved like this:

```python
import lime_config

def my_function():
    opt = lime_config.config.plugins['solution-radek']['my-option']
```
