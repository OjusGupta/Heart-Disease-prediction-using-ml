# Heart Disease Prediction using ML

A healthcare-focused machine learning project that predicts the presence of heart disease using ensemble classification algorithms.

## 🚀 Project Overview
This repository contains end-to-end model development for binary heart disease prediction using patient medical features. It includes:
- data cleaning and preprocessing
- exploratory data analysis (EDA)
- model training and evaluation
- comparison of AdaBoost and Random Forest classifiers

## 📁 Repository Structure
```
Heart-Disease-prediction-using-ml/
├── data/
│   └── heart_disease.csv
├── notebooks/
│   ├── adaboost_classifier.ipynb
│   └── random_forest_classifier.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## 📦 Dataset
- Source: [UCI Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
- Features: 13 medical attributes including age, sex, blood pressure, cholesterol, maximum heart rate, and more
- Target: Heart disease presence (binary classification)

## 🧠 Models Included
- AdaBoost Classifier
- Random Forest Classifier

## ✅ How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/adaboost_classifier.ipynb
jupyter notebook notebooks/random_forest_classifier.ipynb
```

## 📊 Evaluation
The notebooks evaluate models using metrics such as accuracy, precision, recall, and F1-score.

## 🛠️ Requirements
See `requirements.txt` for exact package versions.

## 📌 Notes
- The notebook filenames are renamed for readability and recruiter-friendly presentation.
- Dataset now lives in `data/`.
