# CODSOFT-Iris-Flower-Classification
# Iris Flower Classification

This project uses the classic **Iris flower dataset** to develop and evaluate multiple machine learning models that classify flowers into three species — **Setosa**, **Versicolor**, and **Virginica** — based on their sepal and petal measurements.

---

## Project Overview

The objective is to:
- Train classification models on the Iris dataset.
- Compare model performance using accuracy and confusion matrix.
- Visualise model predictions and feature importances.
- Identify the best-performing model for potential deployment.

---

## Dataset

The **Iris dataset** fro https://www.kaggle.com/datasets/arshid/iris-flower-dataset consists of 150 samples with the following features:

- `sepal_length (cm)`
- `sepal_width (cm)`
- `petal_length (cm)`
- `petal_width (cm)`
- `species` (target class)

The dataset is balanced, with 50 samples per species.

---

## Models Used

Several classification algorithms were trained and evaluated:

- Logistic Regression
- K-Nearest Neighbours (KNN)
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Classifier (SVC)

**GridSearchCV** was employed to optimise hyperparameters, particularly for the SVC model.

---

## Best Model: Support Vector Classifier (SVC)

- **Kernel Used:** `rbf`
- **Accuracy:** 96.7% on the test set
- **Confusion Matrix:** Demonstrated very high performance with minimal misclassifications
- **Feature Importance (via Permutation):**
  - `petal_length` emerged as the most important feature
  - Followed by `sepal_length` and `sepal_width`

---

## Visualisations

-  **Confusion Matrix:** Highlights correct vs incorrect predictions
-  **Actual vs Predicted:** Scatter plot comparing real and predicted labels
-  **Feature Importance:** Bar chart showing influence of features on prediction

---

## Tools & Libraries

- Python (3.8+)
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn


