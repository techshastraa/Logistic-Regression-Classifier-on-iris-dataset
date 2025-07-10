# 🌸 Iris Binary Classification using Logistic Regression

This project applies **Logistic Regression** for **binary classification** on the famous **Iris dataset**. The model predicts flower species based on four features: sepal length, sepal width, petal length, and petal width. It uses `scikit-learn` for model training, evaluation, and visualization.

---

## 📘 Project Description

The Iris dataset includes samples from three flower species. For this project, we reduce the problem to binary classification by selecting only two species (e.g., *Setosa* vs *Versicolor*). The goal is to train a model that accurately classifies flowers into one of the two categories.

The steps include:
- Data preprocessing and feature scaling
- Model training using Logistic Regression
- Evaluation using accuracy, confusion matrix, and ROC AUC score
- Visualization with ROC curve and confusion matrix

---

## 📊 Dataset

- **Source**: `sklearn.datasets.load_iris()`
- **Classes Used**: Two out of the three original classes
- **Features**: Sepal length, Sepal width, Petal length, Petal width

---

## 🔍 Technologies Used

- Python
- scikit-learn
- NumPy
- Pandas
- Matplotlib
- Seaborn

---
              precision    recall  f1-score   support

           0       1.00      1.00      1.00        10
           1       1.00      1.00      1.00        10

    accuracy                           1.00        20
   macro avg       1.00      1.00      1.00        20
weighted avg       1.00      1.00      1.00        20

