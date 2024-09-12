# AI-Powered-Anomaly-Detection-System-for-Financial-Transactions

This project demonstrates an AI-powered anomaly detection system for financial transactions using Python and popular machine learning libraries like scikit-learn. It leverages three different anomaly detection techniques: Autoencoders, Isolation Forest, and One-Class SVM.

## Project Overview

The goal of this project is to identify potentially fraudulent or anomalous transactions within a dataset of financial transactions. This is achieved by training the models on a set of normal transactions and then using them to predict anomalies in unseen data.

## Techniques Used

* **Autoencoders:** Neural networks trained to reconstruct input data. Anomalies are detected by measuring the reconstruction error.
* **Isolation Forest:** An ensemble learning method that isolates anomalies by randomly partitioning the data.
* **One-Class SVM:**  A support vector machine algorithm that learns a boundary around normal data points, classifying anything outside this boundary as an anomaly.
