# Allstate AI Studio — Machine Learning Project

> AI Studio project focused on building an end-to-end machine learning pipeline: data preparation → modeling → evaluation → deployment-ready outputs.

## Overview
This project was completed as part of **AI Studio (Allstate x Break Through Tech AI Studio)**. The goal was to take a real-world dataset and create a reliable ML workflow, including clean data, strong baseline models, and performance evaluation.

**Key outcomes**
- Built a complete ML pipeline from raw data to trained model
- Improved data quality with preprocessing + feature engineering
- Compared multiple models and selected the best-performing approach
- Produced reproducible results (notebook/scripts + requirements)

---

## What I Did
### 1) Data Preparation
- Cleaned missing values, inconsistent categories, and outliers
- Encoded categorical variables (one-hot / label encoding where needed)
- Scaled numeric features when appropriate
- Split dataset into train/validation/test sets

### 2) Feature Engineering
- Created derived features to improve predictive signal
- Performed correlation checks and removed redundant features
- (Optional) Feature selection using importance / statistical filtering

### 3) Modeling
Trained and compared:
- Logistic Regression (baseline)
- Random Forest / Gradient Boosting (strong non-linear baselines)
- (Optional) XGBoost / LightGBM if used in your final model

### 4) Evaluation
Evaluated using:
- Accuracy / Precision / Recall / F1
- ROC-AUC (for classification)
- Confusion matrix + error analysis
- Cross-validation and/or grid search for tuning

### 5) Deployment-Ready Output
- Exported trained model (e.g., `.pkl`)
- Saved preprocessing steps so inference matches training
- Documented how to reproduce results locally

---

## Tech Stack
- **Python**
- **Pandas, NumPy**
- **Scikit-learn**


- **Matplotlib**
- (Optional) **XGBoost / LightGBM**
- (Optional) **Jupyter Notebook**

---

