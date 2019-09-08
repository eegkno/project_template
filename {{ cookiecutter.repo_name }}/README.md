{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}


Project Organization
------------


    ├── .github            <- Github templates
    │
    ├── ci-utils           <- Scripts used for CI/CD
    │
    ├── config             <- This directory contains configuration files used in scripts
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is the creator's initials,
    │                         and a short `-` delimited description, e.g.
    │                         `jqp-initial-data-exploration`.
    │
    ├── scripts            <- Any other scripts
    │
    ├── src                <- Source code to use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │                     predictions
    │   │
    │   ├── utils          <- Scripts for general functionalities
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │
    ├── test               <- Scripts testing functionalities
    │
    ├── .editorconfig      <- Editor configurations for consistent coding styles for multiple
    │                         developers working on the same project across various editors
    │                         and IDEs.
    │
    ├── .flake8            <- Flake8 configuration file for coding stile (PEP8)
    │
    ├── .gitignore         <- Files or paterns to be ignored by git
    │
    ├── .pylintrc          <- Pylint configuration file for source code quality checker
    │
    ├── Jenkinsfile        <- Jenkins configuration file
    │
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    │
    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── pytest.ini         <- Pytest configuration file
    │
    ├── requirements-dev.txt <- Main libraries used for develoment. Dependecies should be omitted.
    │
    ├── requirements.txt   <- Main libraries used for production. Must include fixed version and
    │                         dependencies should be omitted.
    │
    └── setup.py           <- Makes project pip installable (pip install -e .) so src can be imported


--------

## Getting started

Create a symbolic link to the data directory on DLshare:

```
make datalink
```

### Python environment

See this [link](https://githubifc.iad.ca.inet/Datalab-Tutorial/DevOps-Team/wiki) for an explanation of how to set up your environment.

After activating your conda environment, run the following commands as needed:

To install all the Python development libraries

```
make Pydev-install
```

To install all the Python production libraries

```
make Pyprod-install
```

### R environment

To install all the R packages

```
make Rinstall
```

## Running the Pipeline

## Contributing Code

### Data Lab coding guidelines

Please familairize yourself with coding [guidelines](https://pages.githubifc.iad.ca.inet/Datalab-Tutorial/guidelines/index.html)

