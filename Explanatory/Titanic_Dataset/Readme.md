# Titanic Survival Prediction — End-to-End Machine Learning Project

## Overview

This project presents a complete machine learning workflow built on the Titanic dataset. It covers the entire pipeline from raw data preprocessing to model development, evaluation, and interactive visualization.

The objective is to predict passenger survival based on demographic and travel-related features, while maintaining a clean, structured, and reproducible workflow.

---

## Problem Statement

Given passenger data such as age, class, fare, and family relations, the goal is to build a classification model that predicts whether a passenger survived the Titanic disaster.

---

## Workflow Summary

The project is divided into distinct stages:

1. **Data Preprocessing**

   * Handling missing values
   * Encoding categorical variables
   * Removing irrelevant features
   * Producing a clean dataset

2. **Baseline Model**

   * Logistic Regression as an initial benchmark
   * Model evaluation using accuracy and classification metrics

3. **Feature Engineering & Model Improvement**

   * Creation of new features (e.g., FamilySize, IsAlone)
   * Training a more robust model (Random Forest)
   * Comparative analysis of model performance

4. **Interactive Visualization**

   * Plotly-based dashboard for exploratory analysis
   * Interactive insights into survival patterns

---

## Key Insights

* Gender is a strong predictor of survival
* Passenger class significantly influences survival probability
* Fare shows a positive relationship with survival likelihood
* Social structure (family size, traveling alone) impacts outcomes

---

## Project Structure

```
titanic-ml-project/
│
├── notebooks/
│   ├── 01_preprocessing.ipynb
│   ├── 02_baseline_model.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_model_comparison.ipynb
│
├── plotly_notebook/
│   └── interactive_dashboard.ipynb
│
├── train.csv
│
└── README.md
```

---

## Notebooks Description

* **01_preprocessing.ipynb**
  Data cleaning, missing value handling, and encoding.

* **02_baseline_model.ipynb**
  Logistic Regression model training and evaluation.

* **03_feature_engineering.ipynb**
  Creation of new features to improve predictive performance.

* **04_model_comparison.ipynb**
  Training and comparing multiple models.

* **interactive_dashboard.ipynb**
  Plotly-based interactive visualizations for data exploration.

---

## Models Used

* Logistic Regression (baseline)
* Random Forest Classifier (improved model)

---

## Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Plotly
* Google Colab

---

## How to Run

1. Open notebooks in Google Colab
2. Mount Google Drive (if required)
3. Run notebooks sequentially:

   * Preprocessing → Modeling → Comparison → Dashboard

---

## Notes

* The project emphasizes clarity, reproducibility, and structured development.
* Each stage is modular, making it easy to understand and extend.

---

## Outcome

This project demonstrates a complete machine learning pipeline with:

* Clean data handling
* Model development and evaluation
* Feature engineering
* Interactive data visualization

It is designed to reflect both technical understanding and practical implementation.
