# PDM

This is a companion example for the [PDM](https://pydevtools.com/handbook/reference/pdm/) reference page on the [Python Developer Tooling Handbook](https://pydevtools.com).

This package is an example project for building a Python package (i.e., wheel or sdist).
It relies on [PDM](https://pdm.fming.dev) as a build backend with `pyproject.toml`
for configuration.

## Commands:

* Install dependencies and setup project:
```shell
pdm install
```
* Run code:
```shell
pdm run python -c "import demo"
```
* Build:
```shell
pdm build
```
* Upload to PyPI:
```shell
pdm publish
```