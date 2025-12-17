# Breast Cancer Classification using Support Vector Machine (SVM)

This project builds a **binary classification model** using **Support Vector Machine (SVM)** to predict whether a breast tumor is **malignant or benign**. In addition to accuracy, multiple evaluation metrics are used to properly assess model performance, which is crucial for medical datasets.

---

## Problem Statement

Early detection of breast cancer can significantly improve treatment outcomes. This project applies machine learning techniques to classify tumors based on diagnostic features.

---

## Dataset Information

* **Dataset:** Breast Cancer Wisconsin Dataset
* **Source:** `sklearn.datasets.load_breast_cancer`
* **Target Classes:**

  * `0` → Malignant
  * `1` → Benign

---

## Technologies Used

* Python
* scikit-learn
* NumPy

---

## Machine Learning Model

* **Algorithm:** Support Vector Machine (SVM)
* **Kernel:** RBF (Radial Basis Function)
* **Regularization Parameter (C):** 1
* **Gamma:** scale
* **Feature Scaling:** StandardScaler
(why SVM-it's is effective for medical datasets because it handles high-dimensional data well and creates a clear decision boundary between malignant and benign cases.In general term-Support Vector Machine finds the optimal hyperplane that best separates classes by maximizing the margin between them.)
---

## Project Workflow

1. Import required libraries
2. Load the Breast Cancer dataset
3. Split the dataset into training and testing sets
4. Apply feature scaling using StandardScaler
5. Train the SVM classifier
6. Make predictions on test data
7. Evaluate model performance using multiple metrics

---

## Evaluation Metrics Used


* **Accuracy** – Overall correctness of the model
* **Confusion Matrix** – Shows true positives, true negatives, false positives, and false negatives
* **Precision** – How many predicted positives are actually correct
* **Recall (Sensitivity)** – How many actual positives are correctly identified (very important for cancer detection)
* **F1-Score** – Balance between precision and recall
* **ROC-AUC Score** – Measures how well the model separates the two classes

---


---

## Results

<img width="1265" height="814" alt="image" src="https://github.com/user-attachments/assets/683c9f64-f09d-4bd0-ac0e-55acff9104dc" />

---


