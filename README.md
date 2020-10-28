# Store Sales Prediction Model
==============================

A model designed to predict the future sales of a store based on location characteristics.

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
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

## Background
The location of a retail store plays a huge role in it's commercial success. A store location planning team uses various data sources to better understand the potential of candidate locations for new stores in the UK. They need data science help in designing a model that can predict the future sales [normalised_sales] of a store based on location characteristics.

## Objective
The objective of this project is to try different data science and machine learning techniques using real world data.

### Dataset files:

- train.csv
- test.csv

### Columns:

- **location_id:** id of property location
- **normalised_sales:** normalised sales value of store
- **crime_rate:** crime rate in the area (higher means more crime)
- **household_size:** mean household size in the area
- **household_affluency:** mean household affluency in the area (higher means more affluent)
- **public_transport_dist:** index of public transport availability in the area
- **proportion_newbuilds:** proportion of newly built property in the area
- **property_value:** average property value in the area
- **commercial_property:** percentage of commercial properties in the area
- **school_proximity:** average school proximity in the area
- **transport_availability:** availability of different transport
- **new_store:** new Grocery Retail store opened recently
- **proportion_nonretail:** proportion of non-retail commercial properties in the area
- **competitor_density:** density of competitor retailers
- **proportion_flats:** proportion of blocks of flats in the area
- **county:** county code of the area

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
