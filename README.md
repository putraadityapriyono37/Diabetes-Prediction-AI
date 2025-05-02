# Diabetes-Prediction-AI
## Overview
- Dataset: [Diabetes Prediction Dataset (Kaggle)](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)
- Metode: Regresi Logistik, Random Forest, XGBoost
- Demo: [Google Colab Link](https://colab.research.google.com/drive/11FHqe07bvNaNRV-0n20o2Q6-XXkxEH2R?usp=sharing)

## Features
- Gender, Age, Hypertension, Heart Disease, Smoking History, BMI, HbA1c Level, Blood Glucose Level
- Target: Diabetes (0 = Tidak, 1 = Ya)

## Model Performance
| Model              | Accuracy | ROC-AUC |
|--------------------|----------|---------|
| Logistic Regression| 0.85     | 0.92    |
| Random Forest      | 0.87     | 0.94    |
| XGBoost            | 0.88     | 0.95    |

## Requirements
- Python 3.8+
- Libraries: pandas, scikit-learn, matplotlib, seaborn, shap, xgboost
