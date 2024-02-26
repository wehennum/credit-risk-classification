OVERVIEW
This analysis aimed to employ machine learning for predicting lending credit risk, specifically identifying borrowers' creditworthiness. We examined financial data to forecast the probability of loan default. We compared model performances by employing various training techniques to identify the superior one. The loan_status variable played a pivotal role, with 0 being a healthy loan and 1 meaning a high-risk loan. Our analysis was split into several phases, including reading in the data to be able to use for modeling. The next step was splitting data into training and testing sets. Once the data was split we employed logistic regression for loan status predictions, and assessing model performance using metrics like accuracy, precision, and recall (Precision Score, Recall score and F1-Score). Below is the listed results of the findings.


RESULTS

           Label   precision  recall   f1-score  support

Healthy Loan-0       1.00      1.00      1.00     18759
High_Risk-   1       0.87      0.95      0.91       625





SUMMARY 
The model we selected (logistical regression) showed excellent performance in predicting healthy loans (Label 0), achieving perfect precision, recall, and F1-score. For high-risk loans (Label 1), the model maintains strong precision and recall scores of 0.87 and 0.95, respectively, with an overall F1-score of 0.91. This suggests the model effectively identifies both healthy and high-risk loans, with slightly lower precision for high-risk loans. The ability to predict high risk loans is the critical aspect that will allow the bank to make the necessary adjustments to rates or by making the applier put up some sort of asset to
be held to cover the riskiness of the loan. This will help reduce credit risk for the institution offering the loan. 
