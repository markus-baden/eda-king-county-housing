# EDA Project - King County Housing Data

## About this repository

This project was created as part of the data science bootcamp at *neuefische* in December 2022.

Contents of this repository:
* the original assignment can be found in the [assignment.md](assignment.md)
* the main part of the exploratory data analysis (EDA) was done in [this jupyter notebook](EDA.ipynb)
* a short keynote presentation about the results can be found [here](EDA_presentation.pdf)




## Setup

This repo contains a [requirements.txt](requirements.txt) file with a list of all the packages and dependencies you will need. Before you install the virtual environment, make sure to install postgresql if you haven't done it before.

```BASH
brew update
brew install postgresql
```


In order to install the environment you can use the following commands:

```BASH
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```