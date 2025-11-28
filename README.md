---

# Vehicle Kick Risk Prediction (Machine Learning Case Study)

This project develops a supervised machine learning workflow to predict **"kick" risk** (bad-buy likelihood) in automotive auctions.
It applies data cleaning, feature engineering, model tuning, and performance evaluation across several classification algorithms.

## 📊 Project Goals

* Clean and preprocess a multi-feature automotive dataset
* Engineer relevant predictive features
* Train and compare multiple supervised ML models
* Tune hyperparameters using GridSearchCV
* Evaluate performance using accuracy, ROC-AUC, and overfitting diagnostics
* Identify the strongest predictors of bad-buy risk

## 🛠️ Tools & Libraries

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Jupyter Notebook

## 🔧 Models & Techniques

* Decision Tree Classifier
* Regression-based classifiers
* Neural Network classifier (MLPClassifier)
* Train/test split and cross-validation
* GridSearchCV for hyperparameter optimisation
* ROC-AUC, accuracy, confusion matrices
* Feature importance analysis

## 📈 Workflow Overview

1. Loaded and cleaned the automotive dataset
2. Inspected distributions, missing values, and correlations
3. Engineered features including price ratios, warranty cost ratios, and vehicle age
4. Trained several baseline models and compared performance
5. Tuned top-performing models using grid search
6. Evaluated ROC curves, overfitting, and generalisation
7. Analysed key predictors of high-risk kicks

## 📁 Files

* `Vehicle Kick Risk Prediction.ipynb`: Full machine learning pipeline and analysis
* Dataset provided via coursework (not included in repository)

---

Created as part of a machine learning coursework project, demonstrating model evaluation, feature engineering, and supervised learning workflows.

---
