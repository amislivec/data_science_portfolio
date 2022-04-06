# Stroke Prediction

Using machine learning to predict stroke

## Abstract

This project is an analysis of a [stroke indicators dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset).  The analysis prepares the dataset for input to logistic regression and random forest classifiers, which are trained on the indicators to predict the likelihood of a stroke.  The dataset is highly imbalanced, with a 5% stroke positive rate.  The best predictive performance was achieved with a random forest classifier, where class imbalance was accounted for by random undersampling of the stroke negative rate in each bootstrap sample.  After hyperparameter optimization, this model achieved an 85% sensitivity (true stroke positive rate) and a 70% specificity (true stroke negative rate) evalulated via cross validation.

## Notebook

The project is contained in the notebook stroke_prediction.ipynb
