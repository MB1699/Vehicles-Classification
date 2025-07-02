# Vehicles-Classification
A complete ML pipeline to classify vehicle price ranges using real-world listings. Includes feature engineering, training (Decision Tree, Random Forest, XGBoost, SVM, Logistic Regression), and visual performance comparison with ROC, PR curves, AUC, and confusion matrices.

# 🚗 Vehicle Price Classification with Advanced Model Comparison

This project presents a comprehensive classification analysis pipeline that predicts vehicle price categories using machine learning techniques. It includes robust feature engineering, multiple model training, and enhanced visualizations.

---

## 📊 Problem Statement

Given a dataset of used vehicles (Craigslist-style), the goal is to classify each vehicle into one of four price categories:

- **Budget** (<= $8,000)
- **Mid-Range** ($8,001 – $20,000)
- **Premium** ($20,001 – $40,000)
- **Luxury** (>$40,000)

---

## 🛠️ Features

- Automated **data cleaning** and **feature engineering**
- Classification using:
  - Decision Tree
  - Random Forest
  - XGBoost
  - Logistic Regression
  - Support Vector Machine (SVM)
- Metrics comparison:
  - Accuracy, F1, Precision, Recall
  - AUC, Average Precision, Overfitting Gap
- Visualizations:
  - ROC & PR curves
  - Confusion Matrices
  - Lorenz Curve (Cumulative Gains)
  - Feature Importances
  - Model Ranking Bar Charts

---

## 📁 Files Included

| File                            | Description                              |
|------------------------------ --|------------------------------------------|
| `vehicles_classification.ipynb` | Jupyter notebook with full analysis      |
| `Vehicles.csv`                  | Vehicle dataset                          |



