# {{ cookiecutter.project_name }}

[![PyPI](https://img.shields.io/pypi/v/{{ cookiecutter.slug }}.svg)](https://pypi.org/project/{{ cookiecutter.slug }}/){% if cookiecutter.github_username %}
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.slug }}/blob/main/LICENSE){% endif %}
[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg)](https://github.com/RichardLitt/standard-readme)

> {{ cookiecutter.description }}

## Background

Background information goes here.

## Install

You can install with `pip`:

```sh
pip install {{ cookiecutter.slug }}
```

With `poetry`:

```sh
poetry add {{ cookiecutter.slug }}
```

Or with `pipenv`:

```sh
pipenv install {{ cookiecutter.slug }}
```

## Usage

Usage instructions go here.

## Development

This project uses [poetry](https://python-poetry.org/docs/#installation) for dependency management. Make sure [pipx](https://pipx.pypa.io/stable/installation/) is installed (e.g., `brew install pipx` on Mac) and then install poetry with `pipx install poetry`.

Once that's set up, you can install the project dependencies and run various tasks via [`poe`](https://poethepoet.natn.io/poetry_plugin.html) or `poetry run`. You can view all of the available tasks by running `poetry run poe --help` or reviewing the `[tool.poe.tasks]` of the `pyproject.toml` file.

```sh
# Install dependencies
poetry install

# Make sure git is initialized, if not already
git init

# Setup pre-commit and pre-push hooks
poetry run poe pre-commit

# Run linters
poetry run poe lint

# Run tests
poetry run poe test
poetry run poe coverage
# Or
poetry run pytest

# Build the package
poetry build
```

## Contributing

PRs accepted.

This package was created with Cookiecutter and the [sourcery.ai](https://github.com/sourcery-ai/python-best-practices-cookiecutter) project template. Small note: If editing the README, please conform to the
[standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

Apache-2.0, © 2024 {% if cookiecutter.github_username %}{{ cookiecutter.author_name }}{% endif %}
