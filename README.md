# 📩 SMS Spam Classifier

Machine Learning project for classifying SMS messages as Spam or Ham using NLP techniques.

---

## 🚀 Project Overview

This project builds and compares multiple machine learning models for spam detection.

Models implemented:
- Multinomial Naive Bayes
- Logistic Regression
- Logistic Regression (class_weight='balanced')

---

## 📊 Final Results

| Model | Accuracy | Spam Recall | ROC-AUC |
|-------|----------|------------|---------|
| Naive Bayes | 96.68% | 0.75 | — |
| Balanced Logistic Regression | **97.76%** | **0.91** | **0.989** |

Balanced Logistic Regression performed best due to improved handling of class imbalance.

---

## 🧠 Key Concepts Used

- TF-IDF Vectorization
- Train/Test Split
- Class Imbalance Handling
- Confusion Matrix
- ROC Curve
- Precision / Recall Tradeoff

---

## 🛠️ Tech Stack

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## 💡 What I Learned

- Importance of recall in imbalanced datasets
- Why simple models like Naive Bayes work well for NLP
- How class_weight improves minority class performance
- How to interpret ROC-AUC

---
## ▶️ How to Run

1. Install dependencies:

2. Run the notebook.
