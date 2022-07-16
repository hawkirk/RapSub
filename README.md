RapSub
==============================

Project goal: Use the Reddit API to explore data from rap artist subreddits.

Potential research questions:
- Which rapper subreddits are the most active?
- Are some rappers overrepresented by their reddit fanbase when compared to their streaming or sales statistics?
- Which rapper subreddits are the most toxic? (sentiment analysis)

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- Top-level README file
    ├── data
    │   ├── interim        <- Intermediate data that has been transformed
    │   ├── processed      <- Final, canonical data sets for modeling
    │   └── raw            <- Original, immutable data dump
    │
    ├── docs               <- Any relevant documentation, project notes, and/or references
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks for data exploration, mockups, and other small tasks
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    └── src                <- Source code for use in this project.
        ├── __init__.py    <- Makes src a Python module
        │
        ├── data           <- Scripts to download or generate data
        │   └── make_dataset.py
        │
        ├── features       <- Scripts to turn raw data into features for modeling
        │   └── build_features.py
        │
        ├── models         <- Scripts to train models and then use trained models to make
        │   │                 predictions
        │   ├── predict_model.py
        │   └── train_model.py
        │
        └── visualization  <- Scripts to create exploratory and results oriented visualizations
           └── visualize.py

--------

<p><small>Project structure modified from the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>.</p>
