# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Due to the highly imbalanced nature of the dataset, various resampling techniques and models are applied to improve fraud detection performance.

---

## 📂 Dataset
- Dataset: Credit Card Transactions
- Total records: 284,807
- Fraud cases: 492 (~0.17%)
- Highly imbalanced classification problem

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE, ADASYN, RandomOverSampler)
- Joblib

---

## 🧠 Machine Learning Models
The following models were implemented:
- Logistic Regression
- Random Forest
- Decision Tree

---

## 🔄 Handling Imbalanced Data
To address class imbalance, the following techniques were used:
- Random Over Sampling (ROS)
- SMOTE (Synthetic Minority Over-sampling Technique)
- ADASYN (Adaptive Synthetic Sampling)

---

## 📊 Model Evaluation Metrics
Models were evaluated using:
- Confusion Matrix
- Precision, Recall, F1-score
- ROC-AUC Score
- PR-AUC Score (important for imbalanced datasets)

---

## 🏆 Best Model
After training and hyperparameter tuning:

- Model: Random Forest  
- Sampler: SMOTE  
- PR-AUC: ~0.869  
- ROC-AUC: ~0.961  
- F1 Score: ~0.83  

This combination provided the best balance between precision and recall for fraud detection.

---

## 🔧 Project Workflow
1. Data loading and inspection  
2. Handling class imbalance  
3. Train-test split  
4. Model training with pipelines  
5. Model evaluation  
6. Comparison of models  
7. Hyperparameter tuning  
8. Selection of best model  
9. Model saving for deployment  

---

## 💾 Model Deployment
The best model is saved as:

best_fraud_model_tuned.pkl

This can be used for deployment (e.g., Streamlit app).

---

