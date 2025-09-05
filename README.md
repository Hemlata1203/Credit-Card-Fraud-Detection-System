# Credit Card Fraud Detection 🛡️💳

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. The dataset is highly imbalanced (fraud cases are rare compared to normal transactions), so special handling such as resampling and advanced models is required.
The goal is to build and evaluate multiple ML models and identify the best-performing one for fraud detection.

## 📊 Dataset
Source: Kaggle Credit Card Fraud Dataset
Size: 284,807 transactions
Features: 30 (anonymized using PCA, plus Time and Amount)

Target:
0 → Non-Fraud
1 → Fraud

## ⚙️ Technologies Used

Languages: R, Python

Libraries (R):
caret, partykit, pROC, xgboost, ggplot2

Libraries (Python):
scikit-learn, xgboost, imblearn, matplotlib, seaborn

## 🔬 Models Implemented

Logistic Regression

Decision Tree (ctree)

Random Forest

XGBoost

Evaluation using ROC-AUC, Confusion Matrix, and Classification Report


## 📈 Results

XGBoost achieved the highest ROC-AUC score.

Handling class imbalance (SMOTE / resampling) significantly improved fraud detection.

Fraud cases are very rare (~0.17% of all transactions), making precision-recall tradeoff critical.

## 📌 Future Work

Implement deep learning models (ANN, LSTM).

Deploy the best model as a web API for real-time fraud detection.

## 👩‍💻 Author

Hemlata
📧 [hemlata023btaiml22@igdtuw.ac.in]
🔗 [https://github.com/Hemlata1203]
