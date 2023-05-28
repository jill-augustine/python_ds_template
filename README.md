# python_ds_template

A Python data science template for GitHub on which other repos can be based. It is a GitHub-specific alternative to [`cookiecutter`](https://github.com/cookiecutter/cookiecutter).

Components of this repo:
- notebooks directory
- tests directory
- docs directory
- requirements file containing libraries for linting and unit testing
- python-specific .gitignore (taken from GitHub)

## Notes on setuptools and Python Packaging

This repo contains an example `pyproject.toml` file and an example `setup.py` file, called which are more or less equivalent and contain copy/paste code from the setuptools documentation.
Using pyproject.toml is prefered but some features, such as loading requirements from a text file are still in [beta](https://setuptools.pypa.io/en/latest/userguide/pyproject_config.html) so the setup.py file is provided as a legacy alternative.
To use the `pyproject.toml` or the `setup.py`, copy the example file and delete ".example" from the file name.

Assumptions:
- You are using pip>=21.1 and so you can install packages in editable mode without a `setup.py`.

