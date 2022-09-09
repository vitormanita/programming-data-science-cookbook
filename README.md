# novaims-programming-data-science
Overview, summary, and practical exercises on the main topics of Python programming for Data Science.

## How to use
This repository aims at being a compilation of resources to guide you during the Programming for Data Science classes. You can use it as one two ways:

### Option #1: The Noob way
You can use your global/default Python environment installed with Anaconda and focus on the jupyter notebooks inside the `notebooks` folder. <br>

If you try to run the written code and have any errors regarding package version conflits, please look at what version of the problematic package this project uses in the `pyproject.toml` config.

### Option #2: The Jedi way
In this method, instead of using the global Python environment in your machine, you can create an independent virtual environment using *pyenv* with the required specifications for this project.

To do so, please follow the steps in the Development environment chapter bellow.


## Development environment
For the Jedi users.

### Setup

Requirements:
- [pyenv](https://github.com/pyenv/pyenv) (Python version management)
- [poetry](https://python-poetry.org/) (Python dependency management)

```
$ pyenv install 3.8.8
$ poetry install
```

## Author
Vitor Manita (vmanita@novaims.unl.pt)
