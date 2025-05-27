# Loan Default Prediction

This project develops a machine learning model to predict the likelihood of loan default. The goal is to help financial institutions assess borrower risk using predictive modeling techniques, particularly **LightGBM**.

## 📋 Overview

The notebook walks through:
- Data loading and exploration
- Data cleaning and preprocessing
- Handling class imbalance using **SMOTE**
- Model training with **LightGBM**
- Evaluation using classification metrics

## 📁 Dataset

The dataset contains historical loan and borrower information. It includes features such as income, credit score, loan purpose, and more, with the target variable indicating loan default (`1`) or not (`0`).

## ⚙️ Requirements

Install the necessary Python libraries:

```bash
pip install pandas numpy scikit-learn lightgbm imbalanced-learn matplotlib seaborn
