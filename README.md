# Codes-for-Kaggle-Competitions

This repository contains two projects aimed at increasing my knowledge in machine learning and deep learning. I am enthusiastic about these fields and have chosen these projects to explore different aspects of them.


## Table of Contents

- [Projects](#projects)
- [Comparison of ResNet-18 and LeNet-5 Models for MNIST Image Classification](#Comparison-of-ResNet-18-and-LeNet-5-Models-for-MNIST-Image-Classification)
- [Spaceship Titanic Prediction](#Spaceship-Titanic-Prediction)



# Projects

1. Comparison of ResNet-18 and LeNet-5 Models for MNIST Image Classification (https://www.kaggle.com/competitions/digit-recognizer)
2. Spaceship Titanic Survival Prediction (https://www.kaggle.com/competitions/spaceship-titanic)

## Comparison of ResNet-18 and LeNet-5 Models for MNIST Image Classification

This project compares the performance of two popular deep learning models, ResNet-18 and LeNet-5, for image classification on the MNIST dataset. The goal is to determine whether the more complex ResNet-18 model performs better than the simpler LeNet-5 model, which was specifically designed for this dataset.

After training both models for 10 epochs, ResNet-18 achieved a test accuracy of 0.98846, slightly outperforming LeNet-5, which achieved a test accuracy of 0.9815.

## Spaceship Titanic Prediction

This project compares different machine learning algorithms from scikit-learn to determine which one performs the best in predicting the transportation of passengers from the Spaceship Titanic. The efficiency of hyperparameter tuning is analyzed by measuring the time taken to fine-tune the best model (XGBoost) and comparing its performance on the test dataset before and after fine-tuning.

The models compared in this project include:

- RandomForestClassifier
- Support Vector Machines (SVC)
- K-Nearest Neighbors (KNN)
- Logistic Regression
- XGBoost

The final predictions are generated using the best performing and fine-tuned model, XGBoost. After 26 minutes of fine-tuning, the model's accuracy improved by 0.00491. This demonstrates the trade-off between the computational cost of hyperparameter tuning and the potential improvement in model performance.



