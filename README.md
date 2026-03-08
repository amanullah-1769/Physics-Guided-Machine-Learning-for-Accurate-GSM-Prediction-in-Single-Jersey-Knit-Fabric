# GSM Prediction using Machine Learning

A physics-guided machine learning project for predicting **GSM (Grams per Square Meter)** of **Single Jersey knitted fabrics** using yarn and machine parameters.  
The project evaluates multiple regression models and uses explainable AI techniques to understand feature influence.

---

## Project Overview

Accurate GSM prediction is important in textile manufacturing because it affects fabric quality, cost, and production efficiency.  
This project builds machine learning models to predict GSM based on knitting parameters and yarn characteristics.

Key aspects of the project:

- Feature engineering using **Tightness Factor**
- Training and evaluation of **22 regression models**
- Hyperparameter tuning for improved accuracy
- Model explainability using **SHAP** and **LIME**
- Performance comparison to identify the best model

---

## Dataset Features

Typical input variables used in the model include:

- Yarn Count (Ne)
- Stitch Length
- Machine Gauge
- Machine Diameter
- Tightness Factor (engineered feature)

Target variable:

- **Fabric GSM**

---

## Machine Learning Models Used

The following regression models were tested:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree
- Random Forest
- Extra Trees Regressor
- Gradient Boosting
- Support Vector Regression
- KNN Regression
- AdaBoost
- XGBoost
- LightGBM
- CatBoost
- and other regression models

---

## Best Model

The **Extra Trees Regressor** performed best.

**Performance:**

- RMSE ≈ **4.1**
- R² ≈ **0.95**

This indicates high prediction accuracy for GSM values.

---

## Explainable AI

To understand how features affect predictions, the project uses:

- **SHAP (SHapley Additive exPlanations)**
- **LIME (Local Interpretable Model-Agnostic Explanations)**

These methods help visualize:

- Feature importance
- Local prediction explanations

---

## Project Structure
GSM-Prediction/
│
├── data/
│ └── dataset.csv
│
├── notebooks/
│ └── gsm_prediction.ipynb
│
├── models/
│ └── trained_models.pkl
│
├── report/
│ └── GSM_Prediction_Project_Report.pdf
│
└── README.md



---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/gsm-prediction.git
cd gsm-prediction

pip install -r requirements.txt

Required Libraries

numpy
pandas
scikit-learn
matplotlib
seaborn
shap
lime
xgboost
lightgbm
catboost


