# Titanic Survival Exploration

My completed **Project 0** of the Udacity Machine Learning Engineer Nanodegree — the introductory warm-up project. The goal is to hand-build a survival predictor for the RMS Titanic passenger manifest using only manual conditional rules (no learning algorithm), to get a feel for how features relate to an outcome.

## Contents

- `Titanic_Survival_Exploration.ipynb` — the project notebook. It loads the passenger data, defines an `accuracy_score` helper, and builds up a series of increasingly accurate hand-written predictors (`predictions_0` through `predictions_3`): start by predicting everyone dies, then branch on sex, then on age within the male passengers, and finally add class/fare conditions — reaching the project's 80% accuracy target.
- `titanic_visualizations.py` — the provided helper module that draws survival-rate bar charts filtered by feature, used throughout the notebook to decide which condition to add next.
- `titanic_data.csv` — the passenger dataset (the Kaggle Titanic training set).

## Running

```bash
pip install numpy pandas matplotlib jupyter
jupyter notebook Titanic_Survival_Exploration.ipynb
```

It's a Python 2-era notebook; on Python 3 the only likely fixes are `print` statements in any edited cells. You can delete the committed `titanic_visualizations.pyc` — it's a stale bytecode cache.

## Note

This is an introductory Udacity assignment; if you're working through the same Nanodegree, complete it yourself before reading.
