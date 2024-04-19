# colombia jobs

Colombia's jobs on Graphics
  
## Installation guide

Please read [install.md](install.md) for details on how to set up this project.

## What is this project?

El proyecto se basa en un análisis e investigación inicial del empleo o trabajo en Colombia. 

* ¿Cómo ha crecido en la última década?

### Orden de los Jupyter Notebooks

* 0.0. Extracción y descarga de la data en [datos abiertos](https://datosabiertos.bogota.gov.co): [0.0-angellotrivino-download-data](notebooks/0.0-angellotrivino-download-data.ipynb)

* 0.1. Procesamiento y limpieza de la data: [0.1-angellotrivino-processing-data](notebooks/0.1-angellotrivino-processing-data.ipynb)

* 0.2. Exploración de la data: [0.2-angellotrivino-explore-data](notebooks/0.2-angellotrivino-explore-data.ipynb)

#### Graficas en exploración de la data:

* Crecimiento de las personas en edad de trabajar
* Porcentaje de la Tasa de desocupación
* Crecimiento y decrecimiento de los items: Desocupados, Fuerza de Trabajo, Ocupados, Población en edad de trabajar y Población total GEIH DANE

## Project Organization

    ├── LICENSE
    ├── tasks.py           <- Invoke with commands like `notebook`.
    ├── README.md          <- The top-level README for developers using this project.
    ├── install.md         <- Detailed instructions to set up this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures         <- Generated graphics and figures to be used in reporting.
    │
    ├── environment.yml    <- The requirements file for reproducing the analysis environment.
    │
    ├── .here              <- File that will stop the search if none of the other criteria
    │                         apply when searching head of project.
    │
    ├── setup.py           <- Makes project pip installable (pip install -e .)
    │                         so colombia_jobs can be imported.
    │
    └── colombia_jobs               <- Source code for use in this project.
        ├── __init__.py    <- Makes colombia_jobs a Python module.
        │
        ├── data           <- Scripts to download or generate data.
        │   └── make_dataset.py
        │
        ├── features       <- Scripts to turn raw data into features for modeling.
        │   └── build_features.py
        │
        ├── models         <- Scripts to train models and then use trained models to make
        │   │                 predictions.
        │   ├── predict_model.py
        │   └── train_model.py
        │
        ├── utils          <- Scripts to help with common tasks.
            └── paths.py   <- Helper functions to relative file referencing across project.
        │
        └── visualization  <- Scripts to create exploratory and results oriented visualizations.
            └── visualize.py

---
Project based on the [cookiecutter conda data science project template](https://github.com/jvelezmagic/cookiecutter-conda-data-science).