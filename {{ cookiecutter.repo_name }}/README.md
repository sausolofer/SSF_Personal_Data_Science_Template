{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

## Requirements and Uses

### Prerequisites:
To clone and run the project, the following software tools are needed:

* [Git](https://git-scm.com/downloads) 
* [Python3](https://www.python.org/downloads/)
* [Pip3](https://bootstrap.pypa.io/get-pip.py)

This project requieres the libraries described in the requirements.txt file

### Source code:
First, it is highly recommended to fork the project from your personal GitHub account. Then, once the fork is created, download the sources with the command:

`git clone https://github.com/your_user/{{ cookiecutter.repo_name }}.git`
 
 or

`git clone git@github.com:your_user/{{ cookiecutter.repo_name }}.git`


* It can also be downloaded as a .zip file and unzipped.


### Run and Uses:
To run follow you have two options:

#### Using the Make tool:
* For options using Make tool using the terminal, in the proyect directory execute the following command:
`make`

#### Manual configuration:

1. Install the virtual environment: 
  * Installing the environment:`python3 -m pip install virtualenv`
  * Verify instalation: `virtualenv --version`

2. Create a virtual environment and activate it:
  * On Windows: `py -m venv .venv && .venv\Scripts\activate`
  * On linux and Mac: `python3 -m venv .venv && source .venv/bin/activate`

3. Install the libraries contained in the "requirements.txt" file: `pip install -r requirements.txt`

## Development

### Important links:
* Official source code repo: -
* Download releases: -


## Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── datasets
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

## Help and Support

### Documentation
* HTML documentation: An overview of the project's classes and methods is available here.

### Contact:
Feel free to reach out to {{ cookiecutter.project_author_email }} if you have any problems running the code or if you have a question about the repository as a whole. Lastly, if you have any suggestions to improve this repository, create an issue or send an email if that's more applicable.


<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
