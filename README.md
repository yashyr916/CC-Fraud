Credit Card Fraud Detection
Overview
This project focuses on identifying fraudulent credit card transactions to help credit card companies protect their customers from unauthorized charges. The goal is to build a machine learning model capable of distinguishing between fraudulent and non-fraudulent transactions based on transaction data.

Objective
The challenge is to accurately recognize fraudulent credit card transactions, ensuring that customers are not charged for items they did not purchase. This is crucial in minimizing the financial losses for both customers and financial institutions.

Dataset
The dataset used in this project is highly imbalanced, with the majority of transactions being legitimate. It contains transaction details, including:

Time: Time of the transaction
Amount: Transaction amount
V1, V2, ..., V28: Anonymized feature columns representing sensitive data
Class: Target variable where 0 = legitimate and 1 = fraudulent transaction
Key Characteristics:
Imbalanced Data: Only a small percentage of the transactions are fraudulent.
Feature Engineering: Due to anonymization, the focus is on exploring relationships between the features rather than interpreting them directly.
Technologies Used
Python: The core programming language for implementing the project.
Pandas & NumPy: For data manipulation and preprocessing.
Scikit-learn: To build machine learning models.
Matplotlib & Seaborn: For data visualization.
Imbalanced-learn: To handle the class imbalance.
Jupyter Notebook: For the project’s interactive coding environment.
