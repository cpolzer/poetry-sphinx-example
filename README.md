# poetry-sphinx-example

A demo package to support discussion on how to use Poetry and Sphinx together.


## Setup

```bash
poetry install --no-root
```

## Build the package

```bash
# create the html sphinx docs
poetry run task build
# poetry build the packages
poetry build -vvv
```

## How this demo was created

```bash
poetry init
poetry add sphinx
poetry add taskipy
sphinx-quickstart
```