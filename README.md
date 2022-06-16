# Scraping start

This repository contains initial setup, installation, and organisation for exploring web scraping.

## Installation

1. Activate the Pipfile environment

```bash
pipenv shell
```

2. Install all required packages

```bash
pipenv install
```

3. Make Jupyter aware of the environment

```bash
python -m ipykernel install --user --name=`basename $VIRTUAL_ENV`
```

4. Download the appropriate [Chromedriver](https://chromedriver.chromium.org/downloads) and placed the (extracted) file in this directory

## Development

Ensure that you are in the appropriate environment (`pipenv shell`). Then,

```bash
jupyter-lab
```

You may need to skip the hyphen.

```bash
jupyter lab
```

Once the server has loaded, create a new notebook using the environment kernel.