
# Credit Card Fraud Detection using Machine Learning

## Project Overview

This project focuses on detecting fraudulent credit card transactions using supervised machine learning techniques. Since fraudulent transactions are extremely rare compared to legitimate transactions, the dataset is highly imbalanced. To address this, SMOTE (Synthetic Minority Over-sampling Technique) is applied to the training data before building classification models.

---

## Objectives

* Analyze the credit card transaction dataset.
* Handle class imbalance using SMOTE.
* Train multiple machine learning models.
* Evaluate model performance using appropriate metrics.
* Compare models and select the best-performing classifier.

---

## Dataset

**Dataset:** Credit Card Fraud Detection Dataset

**Source:** Kaggle

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Dataset Information

* Total Transactions: **284,807**
* Features: **30**
* Target Variable: **Class**

  * **0** → Legitimate Transaction
  * **1** → Fraudulent Transaction

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Joblib

---

## Project Workflow

1. Data Loading
2. Data Exploration
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Train-Test Split
6. Handle Class Imbalance using SMOTE
7. Train Logistic Regression
8. Train Random Forest
9. Model Evaluation
10. Model Comparison
11. Save the Best Model

---

## Machine Learning Models

* Logistic Regression
* Random Forest Classifier

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* ROC-AUC Score
* Confusion Matrix
* Classification Report

---

## Results

### Logistic Regression

* Accuracy: **98.89%**
* Precision: **11.73%**
* Recall: **86.32%**
* ROC-AUC Score: **95.23%**

### Random Forest

* Accuracy: **99.95%**
* Precision: **89.02%**
* Recall: **76.84%**
* ROC-AUC Score: **96.09%**

---

## Conclusion

Both models performed well in detecting fraudulent transactions. Logistic Regression achieved a higher recall, while Random Forest provided significantly better precision, overall accuracy, and ROC-AUC score. Based on the evaluation metrics, **Random Forest was selected as the final model** for this fraud detection system.

---

## Project Files

* Project2_Fraud_Detection.ipynb
* fraud_detection_model.pkl
* README.md

> The dataset can be downloaded from the Kaggle link provided above.
