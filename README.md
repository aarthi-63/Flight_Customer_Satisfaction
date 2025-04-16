# Flight Satisfaction of Customers – Machine Learning Classification Project
### Problem Statement

The goal of this project is to predict customer satisfaction based on various in-flight and pre-flight service factors. The target variable is binary: Satisfied or Neutral/NotSatisfied. By leveraging machine learning classification techniques, we aim to identify the key drivers of satisfaction and help airlines improve their services.

### Data Preprocessing

Handled missing values

Encoded categorical variables using Label Encoding and One-Hot Encoding where applicable

Feature scaling with StandardScaler

Split the data into train/test (80/20)

### Models Trained & Compared

We implemented and compared the performance of the following classification algorithms:

1. Logistic Regression

2. Decision Tree Classifier

3. Random Forest Classifier

4. K-Nearest Neighbors (KNN)

5. Naive Bayes

### Best Performing Model

Based on our analysis, Decision Tree Classifier performed the best with the highest combination of precision, recall, and ROC AUC score, making it the most suitable for predicting customer satisfaction accurately.
