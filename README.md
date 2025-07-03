# 🧠 Introvert vs Extrovert Prediction (Kaggle Playground S5E7)

This repository contains my solution to the **Kaggle Playground Series - Season 5, Episode 7** competition.

🎯 **Goal:** Predict whether a person is an **Introvert** or **Extrovert** based on personality and social behavior traits.

## ✅ Model Overview

- **Model Used:** Random Forest Classifier  
- **Validation Accuracy:** 96.22%  
- **Approach:** Simple baseline with clean preprocessing, label encoding, and median/mode imputation.

## 📦 Features

- Time Spent Alone
- Stage Fear (Yes/No)
- Social Event Attendance
- Going Outside
- Drained After Socializing (Yes/No)
- Friends Circle Size
- Post Frequency

## 📊 Key Steps

- EDA to understand feature distributions  
- Imputation of missing values (median for numeric, mode for categorical)  
- Label encoding of categorical variables  
- Random Forest model training and validation  
- Submission file creation

## 📤 Submission

Notebook link on Kaggle (public):
👉 [View Notebook on Kaggle](https://www.kaggle.com/code/faizankhandeshmukh/introvert-or-extrovert)

## 🧩 Next Steps

- Try advanced models like XGBoost / LightGBM  
- Apply hyperparameter tuning  
- Use cross-validation  
- Handle class imbalance more explicitly

---

📌 This is a beginner-friendly, clean, and interpretable baseline that performs surprisingly well.
