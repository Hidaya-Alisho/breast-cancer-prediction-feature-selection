# Breast Cancer Prediction Using Feature Selection & Machine Learning

## Overview

This project applies machine learning techniques to predict whether a breast tumor is benign or malignant using the Breast Cancer Wisconsin Diagnostic dataset. The primary focus is on feature selection, model interpretability, and performance comparison using multiple regression-based classifiers.

The goal is to evaluate how different feature selection methods impact predictive accuracy, computational efficiency, and model interpretability.

---

## Business & Clinical Context

Early and accurate breast cancer diagnosis is critical for patient outcomes. Medical datasets often contain a large number of features, many of which may be redundant or irrelevant. This project demonstrates how feature selection techniques can improve model efficiency while maintaining high diagnostic accuracy.

---

## Objectives

- Explore and understand diagnostic tumor features  
- Perform feature selection using KBest and LASSO  
- Build and compare multiple regression-based models  
- Evaluate model performance using accuracy, confusion matrix, and statistical metrics  
- Balance predictive performance with model interpretability  

---

## Methodology

### Data Exploration
- Distribution analysis using histograms  
- Correlation matrix with interpretation  
- Multivariate analysis using top correlated features  

### Preprocessing
- Feature scaling  
- Train-test split  
- Data normalization  

### Feature Selection
- SelectKBest (top-k statistical features)  
- LASSO regression (L1 regularization)  

### Models Built
- Baseline Logistic Regression  
- Regression using KBest-selected features  
- Regression using LASSO-selected features  
- Hybrid regression using combined KBest + LASSO features  

---

## Results

- Baseline Logistic Regression Accuracy: **95.6%**  
- Optimized Model Accuracy (KBest + LASSO): **97.4%**  
- Feature reduction: from **30 → 13 features**  

The combined model demonstrated marginal improvement in accuracy while increasing computational cost. The baseline logistic regression remained a strong, efficient, and interpretable solution for this dataset.

---

## Tools & Technologies

- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)  
- Feature Selection: KBest, LASSO  
- Google Colab  

---

## Interactive Notebook

View the full analysis, modeling pipeline, and visualizations here:

👉 **Google Colab Notebook:**  
[https://colab.research.google.com/drive/1b0StXUhlmGWiXxAZGnCRfDt_CHdRAF_t](https://colab.research.google.com/drive/1b0StXUhImGWiXxAZGnCRfDt_CHdRAF_t)  

---

## Key Takeaways

- Feature selection improves model efficiency and interpretability  
- Logistic regression performs strongly on medical diagnostic datasets  
- Model simplicity is often preferable when accuracy gains are marginal  
- Data-driven feature engineering is critical in healthcare analytics  

---

## Academic Context

This project was completed as part of a Business Analytics & Machine Learning course assignment focused on applied feature selection and predictive modeling. Emphasis was placed on explanation, interpretation, and business communication of results.
