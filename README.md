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


### **Results of the Logistic Regression Model**

* Overall, the model scored an accuracy of 99% inidicating a high performance.
* Healthy loans had a precision of 100% and recall of 99%.
   * Precision score indicates the model is reliable when predicting healthy loans.
   * Recall score indicates the model is effective at capturing majority of the healthy loans.
* High-risk loans had a precision of 85% and recall 95%.
   * Precision score indicates the model is reliable when predicting high-risk loans but 15% of the predictions are incorrect.
   * Recall score indicates the model is effective at capturing most of the high-risk loans, missing only 5% of them.

### **Summary**

Taking into account the results of the model, I would recommend the use of logistic regression because it is good at identifying borrowers with healthy loans as well as those who are at high-risk of defaulting. In the case of this analysis, it is crucial and beneficial to prioritize results for the high-risk loans. Although the model scored high in its performance, I would recommend testing for outliers to ensure the model is balanced as well.
