# cdc-diabetes-indicators-ML-reproducible-pipeline
Reproducible Research ML Pipeline using the CDC Diabetes Health Indicators dataset.

# CDC Diabetes Health Indicators – ML Project

## Overview
This project explores the **CDC Diabetes Health Indicators dataset** (250,000+ US respondents, 21 features) to predict the likelihood of diabetes using machine learning.  
The goal is to build a **reproducible research pipeline** that supports end-to-end ML: data cleaning, training, evaluation, and reporting.

## Research Question
> Can we predict diabetes risk based on demographic, behavioral, and health indicators?

## Dataset
From: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset?resource=download

## Features
- End-to-end ML pipeline (preprocessing → training → evaluation).
- Baseline models: Logistic Regression, Random Forest, XGBoost.
- Metrics: Accuracy, F1-score, ROC-AUC.
- Reproducible with Docker + requirements.txt.
- Research-style report with findings.

## Project Structure
TODO

## Getting Started
```bash
# Clone repo
git clone https://github.com/AlejandroALopez/cdc-diabetes-indicators-ML-reproducible-pipeline.git
cd cdc-diabetes-indicators-ML-reproducible-pipeline

# Install dependencies
pip install -r requirements.txt

# Run training
python src/train.py --model rf
