# mkdocs-macros-gh-release-changelog

![Static Badge](https://img.shields.io/badge/Python-3.8_%7C_3.9_%7C_3.10_%7C_3.11_%7C_3.12-blue?logo=python&logoColor=white)
[![Stable Version](https://img.shields.io/pypi/v/mkdocs-macros-gh-release-changelog?color=blue)](https://pypi.org/project/mkdocs-macros-gh-release-changelog/)
[![stability-wip](https://img.shields.io/badge/stability-wip-lightgrey.svg)](https://github.com/mkenney/software-guides/blob/master/STABILITY-BADGES.md#work-in-progress)

[![Python tests](https://github.com/febus982/mkdocs-macros-gh-release-changelog/actions/workflows/python-tests.yml/badge.svg?branch=main)](https://github.com/febus982/mkdocs-macros-gh-release-changelog/actions/workflows/python-tests.yml)
[![Maintainability](https://api.codeclimate.com/v1/badges/871d0cf1f07cf373c235/maintainability)](https://codeclimate.com/github/febus982/mkdocs-macros-gh-release-changelog/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/871d0cf1f07cf373c235/test_coverage)](https://codeclimate.com/github/febus982/mkdocs-macros-gh-release-changelog/test_coverage)

[![Checked with mypy](https://www.mypy-lang.org/static/mypy_badge.svg)](https://mypy-lang.org/)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v1.json)](https://github.com/charliermarsh/ruff)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![security: bandit](https://img.shields.io/badge/security-bandit-yellow.svg)](https://github.com/PyCQA/bandit)

Inspired by https://djpugh.github.io/mkdocs_github_changelog

## Commands for development

All the common commands used during development can be run using make targets:

* `make dev-dependencies`: Install dev requirements
* `make update-dependencies`: Update dev requirements
* `make fix`: Run code style and lint automatic fixes (where possible)
* `make test`: Run test suite against system python version
* `make check`: Run tests against all available python versions, code style and lint checks
* `make type`, `make format`, `make lint`, `make bandit`: Run the relevant check
* `make docs`: Render the mkdocs website locally
