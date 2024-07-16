# Credit-risk-classification REPORT

## Overview
Developing a model that accurately assesses borrowers' creditworthiness is pivotal for P2P lending platforms. This model enables lenders to gauge the risk associated with lending to individual borrowers, establish suitable interest rates, and make informed decisions regarding loan approvals. By leveraging historical borrower data and various financial indicators, lenders can evaluate the likelihood of default and enhance the reliability of their lending decisions.

In this project, a dataset containing historical lending activity from a peer-to-peer lending company was employed to construct a model capable of identifying borrowers' creditworthiness. The dataset included features such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, count of derogatory remarks, and total debt. The target variable for the analysis was the "loan status," indicating whether a loan is healthy or at risk.

The objective of this analysis was to build and evaluate a model that identifies borrower creditworthiness. The dataset of historical lending activity was split into training and test sets. The dependent variable (target or "y" value) was the loan status, while the independent variables ("x" values) included loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, and derogatory remarks.

### The process involved:
1.	Splitting the data into training and test sets.
2.	Defining the dependent and independent variables.
3.	Creating a logistic regression model and fitting it to the original data.
4.	Using the trained model to make predictions.

# Logistic Regression Model with Original Data:
•	In terms of precision, the model achieved 100% accuracy in predicting healthy loans, but its precision for high-risk loans was 84%. The overall accuracy of the model was 99%.
•	Regarding recall, the model exhibited 99% recall for healthy loans and 94% recall for high-risk loans.

<img width="489" alt="Screenshot 2024-07-16 at 2 55 16 PM" src="https://github.com/user-attachments/assets/fff1e2d3-c957-4ed9-97b5-0a92de24dcf5">


•	From the confusion matrix, the logistic regression model correctly predicted 18,655 loans as healthy and misclassified 110 loans as healthy out of a total of 18,765 healthy loans (low-risk). For high-risk loans, the model correctly predicted 583 loans and misclassified 36 loans out of a total of 619 high-risk loans.
•	The below figure illustrates the confusion matrix, highlighting the imbalance proportions between actual and predicted classes.

<img width="627" alt="Screenshot 2024-07-16 at 4 59 03 PM" src="https://github.com/user-attachments/assets/72ebd31a-7abb-4db7-b387-19208d847b61">

# Summary

Overall, the accuracy of the logistic regression model appears promising for potential implementation in a banking environment. However, to ensure reliability, I recommend initiating a pilot study using fresh data.

It's essential to emphasize that the effectiveness of the creditworthiness model hinges significantly on the quality and relevance of the data utilized. Therefore, securing a comprehensive and dependable dataset is crucial for achieving precise predictions.

Moving forward, a critical next step involves identifying the most pertinent features that influence borrowers' creditworthiness. Conducting a pilot study with new datasets will allow for a thorough assessment of the model's reliability in practical scenarios.# credit-risk-classification
