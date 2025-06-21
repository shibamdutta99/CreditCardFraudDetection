# 🔒 Credit Card Fraud Detection

![Project Banner](./banner.png)

This project aims to predict fraudulent credit card transactions using machine learning techniques. It demonstrates the challenges of working with imbalanced data and focuses on building a robust classification model.

---

## 📌 Project Overview

- **Domain**: Finance / Fraud Detection  
- **Problem Type**: Binary Classification  
- **Tech Stack**: Python, Scikit-Learn, Pandas, NumPy, Matplotlib  
- **Techniques**: Data Preprocessing, Random Forest, Model Evaluation, Handling Imbalanced Data

---

## 🧾 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Description**:
  - 284,807 transactions over two days
  - Only 492 frauds (0.17% fraud rate)
  - Features `V1–V28` are PCA-transformed for anonymity
  - `Amount` and `Time` are real values

---

## 🛠️ Setup Instructions

1. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

2. **Train the Model**
    ```bash
    python train.py
    ```

3. **Output Files**
    - `random_forest_model.pkl`: Trained model
    - `scaler.pkl`: Scaler used in data preprocessing

---

## 🧠 Model Used

- **Random Forest Classifier**
  - `class_weight='balanced'` used to handle imbalance
  - Evaluated using confusion matrix and AUC-ROC

---

## 📊 Results

| Metric       | Value (Sample) |
|--------------|----------------|
| Accuracy     | 0.9991         |
| Precision    | 0.91           |
| Recall       | 0.84           |
| F1 Score     | 0.87           |
| ROC-AUC      | 0.96           |

> 📌 *Values are examples — replace with your actual metrics if available*

---

## 📁 Directory Structure

