# Credit Risk Analysis Report

### **Overview**

The purpose of the analysis was to train and evalute a logistic regression model with the ability to identify the creditworthiness of borrowers. In order to create the model, we were given a dataset of historical lending activities which includes the following information per borrower: loan size, interest rate, income, deb to income ratio, number of credit accounts open, derogatory marks (history of financial difficulties), and the total debt accumulation. Taking into consideration the borrowers' profile, I needed to predict healthy loans (class 0) and loans at high-risk of defauling (class 1). In the historical dataset, there were 75,036 healthy loans and 2,500 high-risk loans that were reported. 

To build the logistic regression model, I first seperated the data into training and testing sets. By using the training set, I was able to teach the model, exposing it to known data. The testing set was then used to evalaute the model's performance on unseen data. To evaluate the model's accuracy performance, a confusion matrix was then generated providing a summary of the predicted results and identifying areas where it may be making errors. In addition to the confusion matrix, a classification report was created to help assess the logistic regression model's performance and reliability in detail.


### **Results of the Logistic Regression Model**

* Overall, the model scored an accuracy of 99% inidicating a high performance.
* Healthy loans had a precision of 100% and recall of 99%.
   * Precision score indicates the model is reliable when predicting healthy loans.
   * Recall score indicates the model is effective at capturing majority of the healthy loans.
* High-risk loans had a precision of 85% and recall 95%.
   * Precision score indicates the model is reliable when predicting high-risk loans but 15% of the predictions are incorrect.
   * Recall score indicates the model is effective at capturing most of the high-risk loans, missing only 5% of them.

### **Summary**

Taking into account the results of the model, I would recommend the use of logisitic regression because it is good at identifying borrowers with healthy loans as well as those who are at high-risk of defaulting. In the case of this analysis, it would be crucial and beneficial to prioritze high-risk loans. Although the model scored high in its performance, I would recommended testing for outliers to ensure the model is balanced as well.
