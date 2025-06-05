# 💳 Credit Card Fraud Detection:

This project implements a machine learning model to detect fraudulent credit card transactions. Utilizing a dataset of anonymized transactions, the model aims to distinguish between legitimate and fraudulent activities effectively.

## 📂 Project Structure

- `Credit_Card_Fraud_Detection.ipynb`: Jupyter Notebook containing data exploration, preprocessing, model training, and evaluation.
- `credit_card_fraud_detection.py`: Python script version of the notebook for streamlined execution.

## 📊 Dataset

The dataset used includes anonymized credit card transactions, each labeled as fraudulent or legitimate. Features are transformed using PCA to protect user privacy.

## 📚 Data Sources

The following datasets and references were used or inspired this project:

- 🔗 [Infosys: Machine Learning for Credit Card Fraud Detection](https://www.infosysbpm.com/blogs/bpm-analytics/machine-learning-for-credit-card-fraud-detection.html)
- 🔗 [GeeksforGeeks: ML Credit Card Fraud Detection](https://www.geeksforgeeks.org/ml-credit-card-fraud-detection/)
- 🔗 [Springer Chapter: Credit Card Fraud Detection](https://link.springer.com/chapter/10.1007/978-981-13-6861-5_15)
- 🔗 [Kaggle Notebook: KMeans Clustering Fraud Detection](https://www.kaggle.com/code/merryyundi/credit-card-frauddetection#Module-7:-KMeans-Clustering)
- 🔗 [Kaggle Notebook: Balancing is Key + PyCaret](https://www.kaggle.com/code/ohseokkim/creditcard-fraud-balance-is-key-featpycaret)

## 🛠️ Features

- Data preprocessing and exploration
- Handling class imbalance using techniques like SMOTE
- Model training (Logistic Regression, Random Forest, etc.)
- Performance evaluation using precision, recall, F1-score, ROC-AUC

## 🚀 Getting Started

1. Install dependencies:

pip install -r requirements.txt

2.  run the script:

python credit_card_fraud_detection.py

## 📈 Results
The model’s performance is measured using:

Confusion Matrix

Accuracy Score

Precision, Recall, F1 Score

ROC Curve & AUC
