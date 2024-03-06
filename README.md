# credit-risk-classification

## Credit Risk Analysis Report
## Overview
The purpose of this analysis is to build and evaluate a machine learning model for credit risk assessment. In this analysis, we utilized logistic regression to predict the likelihood of loan default based on various features provided in the lending dataset. The goal is to assist financial institutions in making informed decisions regarding loan approvals by accurately identifying high-risk loans.

Results

- **Accuracy Score**: 0.99
- **Precision Scores**:
  - Precision Score (Healthy Loan): 1.00
  - Precision Score (High-Risk Loan): 0.86
- **Recall Scores**:
  - Recall Score (Healthy Loan): 1.00
  - Recall Score (High-Risk Loan): 0.91

- Accuracy Score:
The accuracy score of the model is 0.99, indicating that it correctly predicts approximately 99% of the instances in the dataset.

- Precision Scores:
Precision Score (Healthy Loan): 1.00
Precision Score (High-Risk Loan): 0.86
The precision score for healthy loans (label 0) is 1.00, implying that all predictions for healthy loans are correct.
For high-risk loans (label 1), the precision score is 0.86, indicating that 86% of the predicted high-risk loans are accurate.

- Recall Scores:
Recall Score (Healthy Loan): 1.00
Recall Score (High-Risk Loan): 0.91
The recall score for healthy loans (label 0) is 1.00, suggesting that the model identifies all actual healthy loans.
For high-risk loans (label 1), the recall score is 0.91, implying that the model captures 91% of the actual high-risk loans.


Summary
The logistic regression model achieved outstanding performance in predicting credit risk. With an accuracy score of 0.99, the model demonstrates exceptional capability in distinguishing between healthy (0) and high-risk (1) loans. The precision score of 1.00 for healthy loans indicates that all predictions for healthy loans are correct, while a precision score of 0.86 for high-risk loans suggests that 86% of the predicted high-risk loans are accurate. Moreover, the recall score of 1.00 for healthy loans and 0.91 for high-risk loans shows that the model effectively identifies most of the actual instances of each class.

Based on these results, we recommend utilizing the logistic regression model for credit risk assessment. The model's high accuracy, precision, and recall scores indicate its reliability in identifying potential loan defaults. By leveraging this model, financial institutions can mitigate the risk of default, optimize loan approval processes, and make informed decisions to protect their assets and maintain financial stability.

