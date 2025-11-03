# OASIS Alzheimer’s (CDR>0) – XGBoost Baseline

End-to-end machine learning pipeline for dementia prediction (CDR > 0) using the OASIS cross-sectional MRI dataset. Includes preprocessing, feature engineering, and XGBoost classification with ROC, F1, and AUC evaluation. Demonstrates interpretable modeling for Alzheimer’s research.

---

## 🧠 Overview

This project trains an **XGBoost** classifier to predict dementia status (CDR > 0) from the **OASIS cross-sectional** dataset, fetched automatically via **kagglehub** from `jboysen/mri-and-alzheimers`.  
It uses a scikit-learn `Pipeline` with:
- numeric preprocessing (median imputation + standardization)
- categorical preprocessing (most-frequent imputation + one-hot encoding)
- XGBoost classifier with sensible defaults

---
