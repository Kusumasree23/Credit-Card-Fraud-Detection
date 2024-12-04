# Credit-Card-Fraud-Detection
Title: Credit Card Fraud Detection with Machine Learning
Group Member Names :
Kusuma Sree Addageethala

INTRODUCTION:
Credit card fraud detection is a significant challenge for financial institutions, as fraudulent transactions result in considerable financial losses and damage to consumer trust. With the increasing volume of transactions and the complexity of fraud patterns, it has become crucial to develop efficient and automated systems to detect fraud. Machine learning (ML) techniques have proven effective in handling classification problems, such as fraud detection. This paper aims to explore various ML algorithms to identify fraudulent transactions from a large dataset containing both legitimate and fraudulent credit card transactions. The dataset consists of 284,807 transactions, including 492 frauds, with 28 principal components, transaction time, and transaction amounts.

AIM :
The primary aim of this study is to investigate and compare various machine learning classification algorithms for detecting credit card fraud. The goal is to fine-tune and optimize these algorithms to improve fraud detection accuracy and identify the best-performing models in a highly imbalanced dataset. This paper also aims to explore the impact of data preprocessing, such as feature scaling and class balancing, on the performance of fraud detection models.

Github Repo:
https://github.com/Kusumasree23/Credit-Card-Fraud-Detection

DESCRIPTION OF PAPER:
This paper discusses the use of machine learning models for credit card fraud detection. The dataset used in the research contains transaction details and labels indicating whether each transaction is fraudulent or legitimate. The paper covers several stages of the machine learning process, including exploratory data analysis, model selection, algorithm evaluation, and tuning. Different models are tested, such as logistic regression, decision trees, random forests, support vector machines, and k-nearest neighbors, with particular focus on precision-recall curves and F1-scores due to the imbalanced nature of the dataset. The study also explores ensemble methods to improve performance and attempts to use a simple neural network to further investigate its potential in fraud detection

PROBLEM STATEMENT :
The problem addressed in this paper is the detection of fraudulent credit card transactions in a highly imbalanced dataset. Out of 284,807 transactions, only 492 are fraudulent, making it challenging for traditional machine learning algorithms to detect fraud without biasing towards the majority class (legitimate transactions). The aim is to create a model that effectively identifies fraudulent transactions without being overly influenced by the imbalance in the dataset.

CONTEXT OF THE PROBLEM:
The rapid increase in online transactions has led to a surge in credit card fraud, making it essential for financial institutions to develop automated fraud detection systems. Credit card fraud detection is often complicated by the large volume of data and the low occurrence of fraud. This dataset represents real-world transaction data, where fraudulent transactions are rare compared to legitimate ones, making it an ideal example of a class imbalance problem. The challenge is to build a model that can accurately detect these rare fraud cases without overwhelming the system with false positives

SOLUTION:
To solve the problem of credit card fraud detection, various machine learning models were tested, including both linear and non-linear algorithms such as logistic regression, linear discriminant analysis, k-nearest neighbors, decision trees, and random forests. The solution involved preprocessing the data to handle class imbalance through techniques like precision-recall curves, stratified cross-validation, and using ensemble methods. The models were evaluated based on metrics like precision, recall, and F1-score to ensure they effectively detect fraud while minimizing false positives. Additionally, feature standardization was used to improve the performance of some models, such as k-nearest neighbors. The final solution was an ensemble approach using Extra Trees Classifier, which achieved the best F1-score of 0.849. The paper concludes that standardizing data and using ensemble methods significantly improve model performance, and further work on neural networks may be necessary to achieve higher recall and precision.


Explanation:
This paper explores the use of machine learning algorithms to tackle the challenge of credit card fraud detection, a critical issue for financial institutions. Detecting fraud in a large volume of credit card transactions is difficult because fraudulent transactions are much fewer than legitimate ones. This creates a class imbalance problem, where the model may become biased towards predicting legitimate transactions. The goal of the paper is to develop an effective model that can accurately detect fraudulent transactions despite this imbalance.

Dataset:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

