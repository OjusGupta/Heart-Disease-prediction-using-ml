# Heart Disease Prediction using ML

A machine learning project to predict the presence of heart disease using classification algorithms.

## Overview
This project implements predictive models to identify heart disease in patients based on medical metrics using **AdaBoost** and **Random Forest** classifiers.

## Dataset
- **Source**: [UCI Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
- **Features**: 13 medical attributes (age, cholesterol, blood pressure, etc.)
- **Target**: Presence/absence of heart disease

## Models
- **AdaBoost Classifier** - Boosting ensemble method
- **Random Forest Classifier** - Bagging ensemble method

## Project Structure
```
+-- AdaBoost.ipynb              # AdaBoost model implementation
+-- Random Forest.ipynb         # Random Forest model implementation
+-- data/                       # Dataset files
+-- README.md
```

## Requirements
```
pandas
numpy
scikit-learn
matplotlib
seaborn
```

## Usage
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebooks to train and evaluate models
4. Models are compared on metrics: Accuracy, Precision, Recall, F1-Score

## Results
Both models achieve high accuracy in predicting heart disease presence. Random Forest generally provides better feature interpretability for medical decision-making.
