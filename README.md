# FAA Wildlife Strike Damage Prediction

## Overview
This project uses machine learning to predict whether an aircraft wildlife strike will result in aircraft damage based on FAA historical wildlife strike data.

## Problem
Aircraft wildlife strikes are common, but only a small percentage result in actual damage. This creates an imbalanced classification problem.

The goal of this project was to predict **INDICATED_DAMAGE** and improve balanced accuracy through data cleaning, preprocessing, and model selection.

## Models Used
- Logistic Regression
- Random Forest
- HistGradientBoostingClassifier
- Decision Trees
- Naïve Bayes
- k-Nearest Neighbors

## Techniques
- Missing value handling
- Categorical encoding
- Feature engineering
- Data normalization
- Text metadata extraction
- Cross-validation
- Balanced accuracy optimization

## Dataset
FAA Wildlife Strike Dataset (1990–2015)

## Results
Baseline Logistic Regression:
Balanced Accuracy ~0.50

Final HistGradientBoosting / Random Forest:
Balanced Accuracy improved to ~0.63

## Tools
Python  
Pandas  
Scikit-learn  
Jupyter Notebook

## Key Learning
This project helped me build practical experience in data cleaning, feature engineering, handling imbalanced datasets, and evaluating machine learning models on real-world aviation data.
