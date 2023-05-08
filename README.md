![](https://storage.yandexcloud.net/datasouls-ods/static/meta_tags/1200x628.jpg)

# Quora Insincere Questions Classification
[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)
[![Documentation Status](https://readthedocs.org/projects/flake8/badge/?version=latest)](https://flake8.pycqa.org/en/latest/?badge=latest)

## Description
This project was made as part of the ODS course on NLP in the spring of 2023. 
The project is based on the competition https://www.kaggle.com/competitions/quora-insincere-questions-classification.
The purpose of this competition is to create a model that accurately categorizes the questions asked on the Quora site as sincere and not sincere.

## Objective of the project
1. Analyze and apply existing approaches for solving NLP problems in the direction of sentiment analysis for the current competition
2. Determine the best solutions for a similar problem, and analyze and apply the existing SOTA solution
3. Prepare research and code and provide results in the form of a report

## Code quality
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