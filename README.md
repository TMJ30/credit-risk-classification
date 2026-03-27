# Loan Risk Analysis with Logistics Regression

## Overview
The purpose of this analysis was to train and evaluate a logistic regression model capable of identifying the creditworthiness of borrowers. Using a dataset of historical lending activity, the model predicts:
* **Healthy loans (class 0)**
* **High-risk loans (class 1)**

The dataset includes 75,036 healthy loans and 2,500 high-risk loans with borrower features such as:
* Loan size
* Interest rate
* Income
* Debt-to-income ratio
* Number of credit accounts open
* Derogatory marks (financial difficulties)
* Total debt accumulation

## Workflow
1. **Split Data:** Separated into training and testing sets to teach the model and evaluate performance
2. **Train Model:** Logistic regression was trained on the training set
3. **Evaluate Performance:**
   * Generated a confusion matrix to summarize predictions and identify errors
   * Created a classification report to assess precision, recall, and overall reliability

## Results
* **Model Accuracy:** 99%
* **Healthy Loans (Class 0):**
  * Precision: 100% → model is reliable when predicting healthy loans
  * Recall: 99% → model captures the majority of healthy loans
* **High-Risk Loans (Class 1):**
  * Precisions: 85% → 15% of predictions are incorrect
  * Recall: 95% → model captures most high-risk loans, missing only 5%
> The model performs well for both classes, prioritzing the detection of high-risk borrowers while maintaining strong reliability for health loans

## Summary
* Logistic regression is recommended for identifying both healthy and high-risk borrowers
* High-risk loan detection is prioritized due to its importance in landing decisions
* Although performance is strong, further testing for outliers is suggested to ensure model balance and robustness
