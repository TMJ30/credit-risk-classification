# Credit Risk Analysis Report

### **Overview**

The purpose of the analysis was to train and evalute a logistic regression model that has the ability to identify the creditworthiness of borrowers. In order to create the model, we were given a dataset of historical lending activities which includes the following information per borrower: loan size, interest rate, income, deb to income ratio, number of credit accounts open, derogatory marks (history of financial difficulties), and the total debt accumulation. Taking into consideration the borrowers' profile, I needed to predict healthy loans (0) and loans at high-risk of defauling (1). In the historical dataset, there were 75,036 healthy loans and 2,500 high-risk loans that were reported. 

To build the logistic regression model, I first seperated the dataset into training and testing sets. Using the training set, I was able to teach the model by exposing known data to it. The testing set was then used to evalaute the model's performance on unseen data. to evaluate the model's accuracy performance, a confusion matrix was then generated to provide a summary of the predicted results and identify areas where it may be making errors. In addition to the confusion matrix, a classification report was created to help assess the logistic regression model's performance in detail.


### **Results of the Logistic Regression Model**

* the
* For healthy loans the precision and recall scores were 100% and 99% respectively
* For loans at risk of defaulting, the precision and recall scores were 85% and 95% respectively

### **Summary**

Taking into account the results of the model, I would recommend the use of logisitic regression because it is good at identifying borrowers with healthy loans as well as those who are at high-risk of defaultin. In the case of this analysis, it would be crucial and beneficial to predict the those who are at high-risk of defaulting. 
