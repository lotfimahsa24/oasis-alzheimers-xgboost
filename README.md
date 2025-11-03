# 🧠 OASIS Alzheimer’s (CDR>0) – XGBoost Baseline

End-to-end machine learning pipeline for dementia prediction (CDR > 0) using the **OASIS cross-sectional MRI dataset**.  
This project demonstrates an interpretable **XGBoost** model for Alzheimer’s classification using demographic and neuroimaging-derived features.  


## 📘 Overview

The model predicts dementia status (CDR > 0) based on structured features such as age, MMSE, and brain volume metrics.  
It automatically downloads and processes the dataset using **KaggleHub**, builds a **scikit-learn Pipeline**, and evaluates model performance using **LogLoss**, **Accuracy**, **AUC**, and **F1-score**.


## 🧠 Dataset Description

This project uses the **OASIS (Open Access Series of Imaging Studies) Cross-Sectional MRI dataset**, a widely used neuroimaging resource for dementia research.  
The dataset contains **436 participants** aged **18–96 years**, including both healthy individuals and patients with mild to moderate dementia, as determined by the *Clinical Dementia Rating (CDR)*.

### 📊 Key Features
| Feature | Description |
|:--|:--|
| **ID** | Subject identifier (e.g., OAS1_0001_MR1) |
| **M/F** | Biological sex |
| **Hand** | Handedness (R/L) |
| **Age** | Age at time of MRI acquisition |
| **Educ** | Years of education |
| **SES** | Socioeconomic status (1–5 scale) |
| **MMSE** | Mini-Mental State Examination score |
| **CDR** | Clinical Dementia Rating
