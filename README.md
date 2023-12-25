# pulse-eco-ha

![GitHub Workflow Test](https://github.com/mxilievski/pulse-eco-ha/actions/workflows/test.yml/badge.svg)
![GitHub Workflow Build](https://github.com/mxilievski/pulse-eco-ha/actions/workflows/build.yml/badge.svg)

[![PyPI](https://img.shields.io/pypi/v/pulse-eco-ha?logo=pypi&label=PyPI&logoColor=gold)](https://pypi.org/project/pulse-eco-ha)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/pulse-eco)

[![types - Mypy](https://img.shields.io/badge/types-Mypy-blue.svg)](https://github.com/ambv/black)
[![GitHub license](https://img.shields.io/github/license/martinkozle/pulse-eco)](https://github.com/mxilievski/pulse-eco-ha/blob/main/LICENSE)

[![pulse.eco logo](https://pulse.eco/img/pulse-logo-horizontal.svg)](https://pulse.eco)


This project is a customized version based on the [Pulse Eco](https://github.com/martinkozle/pulse-eco) project by [Martin Kozle](https://github.com/martinkozle). The original project is a fantastic initiative, and I want to express my gratitude to Martin and the contributors for their hard work.

## Adjusted Version

This repository serves as an adjusted version tailored for use with Home Assistant. Many thanks to the original developers for laying the groundwork. For detailed documentation, credits, and other information about the original Pulse Eco project, please refer to the [original repository](https://github.com/martinkozle/pulse-eco).

Feel free to explore the original project for a comprehensive understanding of its features and functionality.

## Installation

pulse-eco-ha is avialiable on [PyPI](https://pypi.org/project/pulse-eco-ha):

```console
python -m pip install pulse-eco-ha
```

Requires Python version 3.8+.

## Development

### Install Hatch

<https://hatch.pypa.io/latest/install/>

### Create dev environment

Activate a Python 3.8 environment and run:

```console
hatch env create dev
```

### Install pre-commit hooks

```console
hatch run dev:setup
```

### Create .env file

Set auth credentials in `.env` file:

```console
cp .env.example .env
```

### Before committing

This command must pass without errors before committing:

```console
hatch run dev:check
```
