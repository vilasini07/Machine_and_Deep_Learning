# Drug classification using Logistic Regression and kNN

## Objective
This project builds a Logistic Regression model from scratch to classify drugs based on patient features like age, sex, blood pressure, and cholesterol.
It also compares the performance with a simple k-Nearest Neighbors (kNN) algorithm. The dataset is taken from: https://www.kaggle.com/datasets/prathamtripathi/drug-classification?select=drug200.csv

## Steps followed
1. Loading and cleaning of the dataset
2. Encoding categorical variables (One-Hot + Ordinal Encoding)
3. Scaling of numerical features

## Implementations

- Logistic Regression (using softmax + gradient descent)
- kNN classifier
- Training both models and evaluating the accuracy on test data

## Key Findings
1. Custom Logistic Regression works well for multi-class classification using softmax
2. Proper preprocessing (encoding + scaling) improves model performance
3. Logistic Regression generally gives stable and good accuracy(~92%)
4. kNN provides a simple baseline but may be slightly less consistent depending on data(gives ~85% accuracy)
