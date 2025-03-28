Module 12 Report 


I used a logistic regression model to analyze data to predict healthy loans versus high-risk loans. 
The finicial data used values like loan_size, interest_rate, borrower_income, and borrower debt. 
I processed the data and then split the data into a training set and a testing set, then used a logisitic regression model 
to analyze and predict the data. 

- Healthy Loan Data:
    - Precision: 1.00
    - Recall: 0.99
    - f1-score: 1.00
 
- High-Risk Loan Data:
    - Precision: 0.84
    - Recall: 0.94
    - f1-score: 0.89
  
The Logisitc regression model did especially well in Healthy Loan data. It did just okay with High-Risk loan data. 
The recall of 0.94 suggests that it misses 6% of High-Risk loans which could be detrimental to whatever financial 
institution is running this model. 

In short I would use the Logisitc Regression for Healthy Loan data but defer High-Risk loan data to a different model. 
