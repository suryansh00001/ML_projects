# 🚀 ML Projects

A curated collection of machine learning projects implemented in Python using scikit-learn, XGBoost, and more.  
Each project is based on real-world datasets and demonstrates the full ML workflow — from data cleaning and feature analysis to model building and evaluation.

---

## 📂 Projects Overview

### 🔬 1. Breast Cancer Classifier
- **Notebook:** `Breast_Cancer.ipynb`
- **Dataset:** Breast Cancer Wisconsin Diagnostic
- **Goal:** Classify tumors as Benign or Malignant
- **Models Used:**
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
  - XGBoost 
- **Evaluation Metrics:**
  - Accuracy
  - Confusion Matrix
- **Highlights:**
  - Feature correlation analysis
  - Density plots by diagnosis
  - Accuracy comparison across models using bar plots
  - Final model: Tuned XGBoost (`~99.2%` test accuracy)

---

### 🏠 2. Housing Price Prediction
- **Notebook:** `Housing-rates.ipynb`
- **Dataset:** California Housing Data
- **Goal:** Predict median house value based on location, income, rooms, etc.
- **Model Used:**
  - Linear Regression
- **Key Steps:**
  - Handled missing values in `total_bedrooms`
  - Visualized feature-target relationships
  - Encoded categorical features
  - Scaled numerical features before training
  - Evaluated using RMSE, MAE, and R² score
- **Future Improvements:**
  - Add Decision Tree, Random Forest, Ridge/Lasso Regression
  - Use GridSearchCV for hyperparameter tuning
  - Visualize predicted vs actual prices

---
