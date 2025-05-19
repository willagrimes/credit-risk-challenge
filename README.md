# credit-risk-challenge
Overview
This project aimed to build a machine learning model to predict loan risk levels using data from a peer-to-peer lending platform. Each loan was classified as low-risk (0) or high-risk (1) based on financial attributes such as:

Loan amount
Interest rate
Borrower income
Debt-to-income ratio
Total debt
Number of credit accounts
Derogatory marks

Results
Metric	Low-Risk (0)	High-Risk (1)
Accuracy	99%	99%
Precision	1.00	0.84
Recall	0.99	0.94
F1-Score	1.00	0.89
The model performed exceptionally well, particularly in identifying high-risk loans — a key requirement for minimizing default rates.

Insights
Earlier versions showed weak performance on high-risk loans due to class imbalance. After refining the dataset and features, the model achieved much better balance across both classes.

Conclusion
The logistic regression model is a strong baseline for credit risk assessment. It reliably identifies both safe and risky loans, making it suitable for deployment with further tuning.

Next Steps
Explore other models (e.g., Random Forest, Gradient Boosting)
Fine-tune with hyperparameter optimization
Apply resampling techniques if imbalance issues return
