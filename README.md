# Poetry Python Cookiecutter

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/dtbuchholz/cookiecutter-poetry/blob/main/LICENSE)
[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg)](https://github.com/RichardLitt/standard-readme)

> A minimal Cookiecutter template for creating Python packages with Poetry + common tools

## Background

This project is a Python [Cookiecutter](https://github.com/cookiecutter/cookiecutter) template that includes the following:

- [Flake8](https://flake8.pycqa.org/en/latest/)
- [Black](https://black.readthedocs.io/en/stable/)
- [isort](https://pycqa.github.io/isort/)
- [Mypy](https://mypy.readthedocs.io/en/stable/)
- [pre-commit](https://pre-commit.com/)
- [Poetry](https://python-poetry.org/docs/)
- [Poe](https://poethepoet.natn.io/poetry_plugin.html)

## Install

First, make sure both [`pipx`](https://pipx.pypa.io/stable/installation/) and `cookiecutter` are installed. For example, on Mac:

```bash
brew install pipx
pipx install cookiecutter
```

Then, run the following command:

```bash
cookiecutter gh:dtbuchholz/cookiecutter-poetry
```

This will run your through setup steps and create the templated project.

## Usage

The project uses `poetry` for dependency management and packaging. You'll want to make sure you have it installed:

```bash
pipx install poetry
```

Then, you can install the project dependencies:

```bash
poetry install
```

The README that gets created when the template is generated explains the other functionality.

## Contribute

PRs accepted.

## License

Apache-2.0 © Dan Buchholz
