Purpose:
Use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
Financial data: 
the data includes the following factors:
- loan-size
- interest rate
- borrower_income
- debt-to-income
- number of accounts
- derogatory marks
- total debt

We use logisticRegression model to do our analysis:
The test data shows 100% precision when the laon is health yand low risk but it only shows 86% accuracy with high-risk loan. 
The recall shows 99% for healthy loan and 91% for unhealthy loan. 
Accuracy is 99%. 
Summary
The model only has 100% precision when prediciting healthly loan but only 86% for high risk loan. If the company want to use the model to determine unhealthy loan, this model may not be a good choice.

