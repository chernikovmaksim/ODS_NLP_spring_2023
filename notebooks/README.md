![](https://www.ideassn.org/wp-content/uploads/2017/06/image001-1.png)

# Project
[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)
[![Documentation Status](https://readthedocs.org/projects/flake8/badge/?version=latest)](https://flake8.pycqa.org/en/latest/?badge=latest)

## Цель

## Описание


## Качество кода
isort (https://pycqa.github.io/isort/)

    # config_file: pyproject.toml

    # run isort in root dir with recursion to fix imports
    isort .

    # run isort in root dir with recursion to check imports
    isort . -c

    # run isort in root dir with recursion to fix import
    # in interactive mode
    isort . --interactive


black (https://github.com/psf/black/)

    # config_file: pyproject.toml    

    # run black in root dir with recursion to make
    # code black with skip changing single quote to double
    black . --skip-string-normalization

    # run black in root dir with recursion to make
    # code black
    black .

    # run black in root dir with recursion to check
    black . --check --skip-string-normalization

flake8 (https://flake8.pycqa.org/en/latest/) and flake8-black (https://pypi.org/project/flake8-black/)

    # config_file: setup.cfg

    # run flake8 in root dir with recursion to check code
    flake8 .