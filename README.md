# 📊 Case Study 12: Ensuring Accuracy and Fairness in Credit Risk Prediction

This repository contains all relevant notebooks, reports, and code for **Case Study 12**, which focuses on building an accurate, fair, and regulation-conscious credit risk assessment model using real-world financial data.
This case study was conducted over a period of 1 month, with a weekly time commitment of 25 hours, involving end-to-end data handling, modeling, evaluation, and fairness assessment.

---

## 🧾 Overview

The objective of this project is to develop a machine learning pipeline for predicting credit risk while ensuring:
- Data quality and robustness through preprocessing and outlier handling
- Fairness across sensitive demographic features (e.g., AGE, STATE_OF_BIRTH)
- Reliable model interpretability using SHAP
- Consistent performance across multiple stages of data transformation

---

## 📁 File Structure

| File Name | Description |
|-----------|-------------|
| `Case Study 12 - Ensuring Accuracy and Fairness A Case Study on Quality Assurance in Predictive Analytics for Credit Risk Assessment.docx` | Casestudy document mentioning the Problem Statement |
| `Case study-12 Final Report.pdf` | Final report of the case study |
| `PAKDD_Modelling_data.csv` | Cleaned and structured modeling dataset used throughout the project |
| `PAKDD_EDA__Case_study_12.ipynb` | Exploratory data analysis and statistical profiling of the dataset |
| `PAKDD_preprocessing.ipynb` | Detailed preprocessing steps on data upto model building and evaluation |
| `General_Preprocessing_pipeline__Case_Study_12.ipynb` | A reusable, automated preprocessing + modeling pipeline for credit datasets |
| `Preprocessing steps on PAKDD dataset- Case study 12.pdf` | An intermediate document recording various experiments |

---

## 🧪 Key Techniques Applied

- Missing value imputation (mode/median/‘Missing’ label)
- Outlier detection (IQR, Z-score) and winsorizing
- Feature selection (VIF, chi-square, Cramér’s V)
- SMOTE and class weight balancing for minority class
- Model training (LogReg, RF, XGBoost, VotingClassifier)
- SHAP for explainability and Fairlearn for fairness auditing
- Fairlearn for detecting and mitigating bias

---

## 📌 How to Use

1. Open `PAKDD_EDA__Case_study_12.ipynb` to explore the initial dataset and insights.
2. Proceed to `PAKDD_preprocessing.ipynb` to follow detailed transformation steps.
3. Refer to `General_Preprocessing_pipeline__Case_Study_12.ipynb` to reuse or adapt the full pipeline on similar datasets.
4. Refer to `Preprocessing steps on PAKDD dataset- Case study 12.pdf` document for intermediate observations during various experimentation of the case study.
5. Refer to `Case study-12 Final Report.pdf` for final report of the case study including, Problem statement, methodology, insights and conclusion.

---



