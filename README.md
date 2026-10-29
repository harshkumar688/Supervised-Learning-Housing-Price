#  Supervised Learning: Housing Price & Titanic Survival Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Overview
This repository contains solutions for **Week 2: Supervised Learning (Regression & Classification)**. The deliverables include building and evaluating regression and classification algorithms on two benchmark datasets.

---

## 🛠️ Tasks & Projects Covered

### 1. Mini Project 2: House Price Prediction Model (Linear Regression)
* **Goal**: Predict continuous housing prices based on features such as area, bedrooms, bathrooms, stories, parking, and amenities.
* **Pre-processing**: Binary mapping (`yes`/`no` $\rightarrow$ `1`/`0`) and One-Hot Encoding for categorical features (`furnishingstatus`).
* **Evaluation Metrics**:
  * **$R^2$ Score**: `0.6529` (65.3% variance explained)
  * **MSE**: `1.754 × 10¹²`

### 2. Assignment 2: Titanic Survival Prediction (Logistic Regression)
* **Goal**: Classify whether a passenger survived (`1`) or died (`0`).
* **Evaluation Metrics**:
  * **Accuracy**: `81.01%`
  * **Confusion Matrix**:
    * **TN**: 90 | **FP**: 15
    * **FN**: 19 | **TP**: 55

---

## 📊 Visualizations
The actual vs. predicted house prices scatter plot demonstrates strong positive alignment with the baseline identity line.

---

## 📂 Repository Contents
* `Housing.csv`: Dataset for house price regression modeling.
* `housing_pred_vs_actual.png`: Visual evaluation plot for house price predictions.
* `README.md`: Project documentation.
