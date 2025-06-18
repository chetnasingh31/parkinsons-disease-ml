# 🧠 Parkinson’s Disease Detection Using Machine Learning

## 📌 Project Overview

This project aims to build a machine learning model to detect Parkinson’s Disease based on biomedical voice features. The dataset used contains voice measurements such as frequency, jitter, shimmer, and other acoustic features commonly affected by Parkinson’s.

The model is trained to classify whether a patient has Parkinson’s Disease (`status`: 1) or not (`status`: 0). The goal is to demonstrate predictive analysis using feature selection, model training, and evaluation.

---

## 📂 Dataset

- **Source:** Kaggle – Parkinson’s Disease Detection
- **Records:** ~195 samples
- **Features:** 22 voice measurements + target label (`status`)
- **Target Variable:** `status` (1 = Parkinson's, 0 = Healthy)

---

## ⚙️ Technologies & Libraries

- Python
- scikit-learn
- pandas
- matplotlib
- seaborn
- Google Colab

---

## 🧪 ML Process

### 1. Data Preprocessing
- Dropped non-numeric column (`name`)
- Standardized features using `StandardScaler`

### 2. Model Building
- Trained multiple classifiers:
  - Random Forest ✅
  - Logistic Regression
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)

### 3. Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
- ROC Curve & AUC Score
- Feature Importance Visualization

---

## ✅ Results

- **Best Accuracy:** ~XX% (Random Forest)
- **ROC AUC Score:** ~XX
- **Top Features:** MDVP:Jitter(%) and PPE showed strong influence on predictions.

---

