# Bank Customer Churn Prediction

Welcome to the Bank Customer Churn Prediction repository! This project focuses on predicting customer churn in a bank using machine learning techniques. The dataset used in this project is derived from the Bank Customer Churn Prediction dataset, where the goal is to forecast whether a bank customer will churn or not.

## Introduction

The dataset for this project was generated from a deep learning model trained on the Bank Customer Churn Prediction dataset. While feature distributions closely resemble the original dataset, they are not identical. Both the original dataset and the generated dataset are included in this repository for reference.

- `train.csv`: The training dataset, where `Exited` is the binary target.
- `test.csv`: The test dataset, where the objective is to predict the probability of `Exited`.
- `sample_submission.csv`: A sample submission file provided in the correct format.

## Approach

In this project, I explore various machine learning algorithms to predict customer churn based on the provided dataset. After data preprocessing and exploratory data analysis, we build several models and evaluate their performance using appropriate metrics.

## Conclusion

Based on our analysis, I have identified key features that significantly influence customer churn, including:

- Number of products held by the customer
- Activity status of the customer
- Age
- Geography
- Gender
- Account balance

Utilizing these insights, we can provide recommendations to reduce customer churn and improve customer retention strategies.
