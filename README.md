# towles-tool

[![Release](https://img.shields.io/github/v/release/ChrisTowles/towles-tool)](https://img.shields.io/github/v/release/ChrisTowles/towles-tool)
[![Build status](https://img.shields.io/github/actions/workflow/status/ChrisTowles/towles-tool/main.yml?branch=main)](https://github.com/ChrisTowles/towles-tool/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/ChrisTowles/towles-tool/branch/main/graph/badge.svg)](https://codecov.io/gh/ChrisTowles/towles-tool)
[![Commit activity](https://img.shields.io/github/commit-activity/m/ChrisTowles/towles-tool)](https://img.shields.io/github/commit-activity/m/ChrisTowles/towles-tool)
[![License](https://img.shields.io/github/license/ChrisTowles/towles-tool)](https://img.shields.io/github/license/ChrisTowles/towles-tool)

Helper cli commands from a developer

- **Github repository**: <https://github.com/ChrisTowles/towles-tool/>
- **Documentation** <https://ChrisTowles.github.io/towles-tool/>

## Getting started with your project


### Pre-requisites

- `uv` - https://docs.astral.sh/uv/getting-started/installation/#standalone-installer
- `make` - https://www.gnu.org/software/make/

### Set Up Your Development Environment

Setup Requires uvenv. See [here](https://fpgmaas.github.io/cookiecutter-uv/getting-started/#set-up-your-development-environment) for more details.

Then, install the environment and the pre-commit hooks with

```bash
make install
```

### Commit the changes

To finalize the set-up for publishing to PyPI, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/publishing/#set-up-for-pypi).
For activating the automatic documentation with MkDocs, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/mkdocs/#enabling-the-documentation-on-github).
To enable the code coverage reports, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/codecov/).

## Releasing a new version

- Create an API Token on [PyPI](https://pypi.org/).
- Add the API Token to your projects secrets with the name `PYPI_TOKEN` by visiting [this page](https://github.com/ChrisTowles/towles-tool/settings/secrets/actions/new).
- Create a [new release](https://github.com/ChrisTowles/towles-tool/releases/new) on Github.
- Create a new tag in the form `*.*.*`.

For more details, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/cicd/#how-to-trigger-a-release).

## Brother's Contract

- 2025-06-07: Patrick agreed that while he loves rust. he can not add it to this project until he first addes and extendsion system to do it first.


## Blog Posts

Chris Also keeps a blog where he writes about his learnings. Check it out here: https://chris.towles.dev/ and follow him on twitter: https://twitter.com/Chris_Towles
