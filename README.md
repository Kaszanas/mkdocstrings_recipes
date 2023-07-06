# Reproduction of mkdocstrings Recipes

This repository contains a minimal reproduction example of the [mkdocstrings Recipes](https://mkdocstrings.github.io/recipes/) failing to generate API reference documentation.

## Steps to Reproduce

1. Clone this repository.
2. Create a virtual environment `python -m venv venv`.
3. Activate the virtual environment.
4. Install the requirements `pip install -r requirements.txt`.
5. Run `mkdocs build`.
6. Run `mkdocs serve`.

Code Referenceas set in `mkdocs.yml` is pointing towards a route `http://127.0.0.1:8000/reference/SUMMARY/` which displays an empty page.

Further documentation for `mkdocstrings` recipes is required, and a minimal working example would be helpful.

## Worth Noting

The requirements contain additional plugins for `mkdocs`. Please see the `requirements.txt` file for more information.