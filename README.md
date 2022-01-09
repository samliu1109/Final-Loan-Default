# Final-Loan-Default

Executive Summary

Problem 
* Credit risk management is important for financial institutions. Why? There is a vast number of loan clients, with many of them potentially in danger of being unable to repay. The default loan will cause an adverse effect on the profitability of banks; it can affect the amount of dividend to be paid to shareholders. Thus, if we could “see into the future” and know in advance which clients are likely to default, we could address issues before they arise to mostly mitigate the loss.

Key Findings 
1.	The last payment amount is the second important variable in the model. It shows that the more the customer pays in his last payment, the less likely the customer will default on the loan.  
2.	The interest rate on loans is the third important variable in the model. It indicates that the customer will be more likely to default on the loan if the interest rate increases.
3.	The customer's annual income is the fourth important variable in the model. The model shows that the customer's higher income, the less likely the customer will default on the loan. 
4.	The model shows that when the total amount committed to the loan increases, the customer will most likely default on the loan.
5.	The number of payments on the loan is an important variable in the model. For example, the customer with 36 months of payments on the loan is 2 times more likely to default on the loan than the customer who has 60 months of payments.

Model Performance Summary & Interpretation 
1.	Comparing the three models, MLP, Random Forest, and Xgboost in the analysis, the MLP shows the highest area under the curve, roughly 97%, which means only a 3% misclassification rate. 
2.	The MLP has the lowest misclassification rate among the three models, indicating the best model to fit the data. In addition, the lowest mean of log loss shows a little error rate. 
3.	Looking at the precision rate, how many loans in all the customers' loans are labeled as default. The MLP has the second-highest precision to label the correct loan default.
4.	Looking at the recall rate, the customers have the real loan default; how many have been identified. Though the random forest has the highest precision, its AUC and recall rate is not better than MLP. The MLP has the highest recall rate to identify the many actual loan default.
5.	The F1 score is a combined metric, the harmonic mean of precision and recall. Looking at the chart, the MLP has the highest F1 score, indicating that both precision and recall in the MLP model are the highest compared with random forest and xgboost.

Recommendations  
1.	The financial institutions should focus on the customers who pay little in their last payment, tracking them to prevent their high probability of defaulting on their loans. For the email domains of the transactors that has counted as high frequency used in fraud transactions, tracking them to prevent a fraud transaction in advance.  
2.	Financial institutions should carefully set up the range of the loans' interest rate to avoid that high probability of defaulting loan when the interest rate is too high. In addition, to find out the optimal interest rate that most customers will pay and get the most profit. 
3.	Financial institutions should categorize their customers by their annual income. The customers with low income would be the high-risk customer to default on loans. Financial institutions could identify them and measure to prevent default from happening. 

