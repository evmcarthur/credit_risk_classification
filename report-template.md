# Module 12 Report Template

## Overview of the Analysis

The purpose of this credit risk analysis is to assess the performance of a machine learning model designed to predict credit default risk for potential borrowers. By evaluating the accuracy, precision, and recall of the model, we can determine its suitability for implementation within the company's credit approval process. The analysis will provide insights into the model's predictive capabilities, allowing the company to make informed decisions about approving or rejecting loan applications.

The data set contained historical lending activity from a peer to peer lending services company and is being used to try to establish a model that can predict the risk of loans in the future and the subsequent credit worthiness of borrowers using over seventy seven thousand loans. 

The data set was placed into a data frame and then split into testing and training data sets. A logisticRegression model, confusion matrix and classification report were used to assess the model's performance. 

## Results

After evaluating the machine learning model's performance on the credit risk dataset, the following results were obtained:

Accuracy: 99%
Precision: 100% for healthy loans & 85% for high risk loans - 92% average
Recall: 99% for healthy loans & 91% for high risk loans - 95% average 


## Summary

The machine learning model exhibits a very high accuracy of 99%, indicating that it correctly predicts credit defaults and non-defaults in most cases. Additionally, the model achieves a precision score of 92%, suggesting that out of all the instances it predicts as credit defaults, 92% are genuinely defaults. This precision level is acceptable and ensures that the company can minimize the risk of approving loans for applicants who might default.

The model's high recall score of 95% is particularly noteworthy. This indicates that the model effectively captures a significant portion of actual credit defaults. In other words, it identifies 95% of all borrowers who are likely to default. High recall is crucial for the company as it helps in minimizing the number of false negatives (i.e., approving loans for applicants who would eventually default). Reducing false negatives is of paramount importance to mitigate potential losses for the company.

Given the high accuracy, precision, and excellent recall, I recommend implementing this machine learning model for use by the company. It is essential to consider that credit risk analysis prioritizes recall over precision, as avoiding false negatives (missed defaults) is more critical than minimizing false positives (incorrectly flagged defaults). This model can significantly improve the company's credit approval process by identifying high-risk applicants more effectively and helping to reduce potential credit losses.

