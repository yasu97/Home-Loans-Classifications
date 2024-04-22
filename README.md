# Home-Loans-Classifications
The housing market, a cornerstone of economic stability, faces significant risks amid soaring prices and mounting mortgage delinquencies in Canada. Drawing parallels to the 2008 housing crisis, this paper examines the intersection of risk management and technological innovation in loan approval processes. Considering the exponential risk and complexity of home loans, we proposed a machine learning model to better assess home loan approvals in a more accurate and efficient way.

This Python project begins by exploring the dataset. We then clean, transform, and visualize the data to gain a better understanding. Next, we implement five different machine learning models to assess their accuracies and select the best-performing algorithm for the dataset, aiming to generate the optimal business solution.


# Dataset-Overview

The dataset, collected by Konapure [https://www.kaggle.com/datasets/rishikeshkonapure/home-loan-approval] for Dream Housing Finance company, consists of a train and test set, each with 13 columns. The columns and encoded values are as follow:

* Loan_ID
* Gender - Female: 0; Male: 1
* Married – No: 0; Yes: 1
* Dependents – 0: 0 ; 1: 1; 2: 2; 3+:3
* Education – Graduate: 0; Not Graduate: 1
* Self_Employed – No: 0; Yes: 1
* ApplicantIncome
* CoapplicantIncome
* LoanAmount
* Loan_Amount_Term
* Credit_History: No: 0; Yes: 1
* Property_Area: Rural: 0; Semiurban: 1; Urban: 2
* Loan_Status (only train set)
