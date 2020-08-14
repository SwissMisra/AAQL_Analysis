Asian-American Quality of Life Analysis
==============================

This is a analysis of a dataset from the city of Austin, Texas on quality of life amongst Asian-American populations.

Link to the original report and dataset is available at:
https://data.austintexas.gov/City-Government/Final-Report-of-the-Asian-American-Quality-of-Life/hc5t-p62z

This analysis utilizes feature engineering and modeling tools in the scikit-learn, seaborn, and PyCaret packages. These models indicate that the primary features of this survey that drive self-reported quality of life focus on mental health, English-speaking ability and satisfaction with housing, followed by several features around having a close-knit community.

The dataset also includes a processed dataframe with 4, 8, and 25 cluster labels, as a resource for future analysis and projects.

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── interim        <- Intermediate datasets: variable groups, pre-processing steps, etc.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- Raw dataset from data.austintexas.gov.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Supplemental materials provided with dataset.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, i.e. created with '$conda list --explicit > requirements.txt'
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
