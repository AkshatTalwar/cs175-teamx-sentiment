# IMDB Sentiment Analysis

A notebook-based sentiment classification baseline for IMDB movie reviews. The project demonstrates a complete classical NLP workflow: text vectorization, model training, probability calibration, evaluation, and an interactive prediction interface.

## What is implemented

- IMDB dataset workflow with 25,000 training and 25,000 test reviews
- TF-IDF text features
- Logistic regression sentiment classifier
- Calibrated prediction probabilities
- Accuracy and F1 evaluation
- Gradio interface for testing custom reviews

## Baseline results

| Metric | Score |
| --- | ---: |
| Accuracy | 0.879 |
| F1 score | 0.879 |

## Run the project

Open [`notebooks/week1_baseline_imdb.ipynb`](notebooks/week1_baseline_imdb.ipynb) in Jupyter or Google Colab and run the cells from top to bottom.

## Technology

`Python` `scikit-learn` `TF-IDF` `Logistic Regression` `Gradio` `Jupyter`

## Current scope

This repository is an interpretable classical-ML baseline. Transformer-based experiments and production packaging are future extensions, not current features.
