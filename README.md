🧠 Fraud Detection using Logistic Regression
📌 Project Overview

This project focuses on detecting fraudulent transactions using Logistic Regression. It leverages a Kaggle dataset containing anonymized credit card transaction data.
The goal is to build a supervised machine learning model capable of distinguishing between legitimate (non-fraud) and fraudulent transactions.

⚙️ Technologies Used

Python

Pandas, NumPy – Data preprocessing and analysis

Matplotlib, Seaborn – Data visualization

Scikit-learn – Model building, evaluation, and metrics

🧩 Model Used

Algorithm: Logistic Regression

Type: Binary Classification

📊 Model Performance
Metric	Score
Accuracy	76%
Precision (Class 0)	1.00
Recall (Class 0)	0.76
F1-Score (Class 0)	0.86
ROC-AUC Score	0.799

⚠️ Note: The model performs well on non-fraud cases but struggles with detecting frauds due to class imbalance — a common challenge in real-world fraud detection. Future improvements can include SMOTE, Random Forests, or XGBoost to handle imbalance.

📁 Dataset

Source: Kaggle Credit Card Fraud Detection Dataset

Size: 284,807 transactions

Classes:

0 → Non-Fraudulent

1 → Fraudulent

🚀 Future Improvements

Implement SMOTE or ADASYN for class balancing

Try Random Forest, XGBoost, or Neural Networks

Deploy the model using Streamlit or Flask

🧾 How to Run

Clone this repository

git clone https://github.com/yourusername/fraud_detection.git
cd fraud_detection


Install dependencies

pip install -r requirements.txt


Run the notebook

jupyter notebook fraud_detection.ipynb

💡 Key Learning

This project highlights the process of handling imbalanced datasets, performing feature scaling, and evaluating classification models using ROC-AUC and F1-scores.
