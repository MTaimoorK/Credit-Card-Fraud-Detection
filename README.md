# _Credit Card Fraud Detection_

## Overview

This project focuses on detecting credit card fraud using machine learning techniques. The dataset used for this analysis is "creditcard.csv," containing credit card transactions with features such as transaction amount, time, and various anonymized variables.

## Data Exploration

The dataset is explored to understand its structure and characteristics. The analysis includes checking for missing values, exploring the distribution of legitimate and fraudulent transactions, and comparing statistical measures between the two.

## Data Preprocessing

To address the class imbalance, the dataset is balanced using under-sampling. Legitimate transactions are randomly sampled to match the number of fraudulent transactions, resulting in a new dataset ("new_df") used for training the model.

## Model Training

A logistic regression model is chosen for its simplicity and effectiveness in binary classification tasks. The dataset is split into training and testing sets, and the model is trained on the training data.

## Model Evaluation

The model's performance is evaluated on both training and testing datasets. The accuracy, F1 score, confusion matrix, ROC curve, and precision-recall curve are utilized to assess the model's effectiveness in identifying fraudulent transactions.

### Results

- **Training Accuracy:** 92%
- **Testing Accuracy:** 89%
- **F1 Score (Training):** 0.92
- **F1 Score (Testing):** 0.89

## Conclusion

The project demonstrates a successful application of machine learning in credit card fraud detection, achieving high accuracy and F1 scores on both training and testing datasets. The confusion matrix and ROC curve visualizations provide insights into the model's performance, showcasing its ability to distinguish between legitimate and fraudulent transactions.

**Note:** The code and analysis provided here are for educational purposes and may require further refinement for deployment in a real-world scenario.
