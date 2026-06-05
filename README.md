# Credit Card Fraud Detection System
# Abstract
In today’s digital world, the use of credit cards and online transactions has increased rapidly. Along with this growth, credit card fraud has also become a serious issue. This project focuses on developing a machine learning-based system to detect fraudulent transactions. Since fraud cases are very rare compared to normal transactions, the dataset used in this project is highly imbalanced. To overcome this problem, oversampling techniques were applied to improve the model’s performance.

# Introduction
With the increase in online payments, detecting fraudulent transactions has become very important for banks and financial institutions. Traditional methods are not efficient in identifying new types of fraud. Machine learning provides a better approach by analyzing patterns in transaction data. In this project, a model is built to classify transactions as either genuine or fraudulent.

# Objectives

* To build a system that detects credit card fraud using machine learning
* To handle imbalance in the dataset effectively
* To train and test a classification model
* To improve accuracy and reliability of fraud detection

# Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Imbalanced-Learn
* Matplotlib

# Methodology
# Data Collection
The dataset used in this project is taken from Kaggle and contains information about credit card transactions, including both normal and fraudulent cases.
# Data Preprocessing
First, the dataset was loaded and checked for any missing values. Then, the input features and output labels were separated. The data was also scaled to make it suitable for machine learning algorithms.
# Handling Imbalanced Data
Since the number of fraudulent transactions is very low compared to normal ones, Random Oversampling technique was used to balance the dataset.
# Model Training
The processed data was divided into training and testing sets. A machine learning model was then trained to classify transactions.
# Model Evaluation
The performance of the model was evaluated using:
* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Score

# Results
After applying oversampling and training the model, the system showed good performance in detecting fraudulent transactions. The evaluation results indicate that the model can differentiate between genuine and fraud transactions effectively.

## Applications
* Used in banks to prevent fraud
* Helps in securing online payments
* Useful in monitoring financial transactions
* Supports risk management systems

## Conclusion

This project shows how machine learning can be used to detect credit card fraud. By handling the imbalance in data and applying proper techniques, the system can improve fraud detection and reduce financial losses.

## Project Details

* Developed using Python and Jupyter Notebook
* Dataset: Kaggle Credit Card Fraud Dataset
* Type: Machine Learning Classification Project
  
