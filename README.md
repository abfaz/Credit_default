## Project Name - Bike Sharing Demand Prediction


## Project Description 
In recent years, the credit card issuers in Taiwan faced the cash and credit card debt crisis and the delinquency is expected to peak in the third quarter of 2006 (Chou,2006). In order to increase market share, card-issuing banks in Taiwan over-issued cash and credit cards to unqualified applicants. At the same time, most cardholders, irrespective of their repayment ability, overused credit card for consumption and accumulated heavy credit and cash–card debts. The crisis caused the blow to consumer finance confidence and it is a big challenge for both banks and cardholders. This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.
## Dataset Description
The dataset used for credit card default prediction typically contains historical information about credit card holders and their payment behavior.

Here is a description of the common features or attributes found in a credit card default prediction dataset:

ID: ID of each client
LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit
SEX: Gender (1=male, 2=female)
EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown, 0=unkown)
MARRIAGE: Marital status (1=married, 2=single, 3=others)
AGE: Age in years
PAY_0: Repayment status in September, 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months,.....,8=payment delay for eight months, 9=payment delay for nine months and above)
PAY_2: Repayment status in August, 2005 (scale same as above
PAY_3: Repayment status in July, 2005 (scale same as above)
PAY_4: Repayment status in June, 2005 (scale same as above)
PAY_5: Repayment status in May, 2005 (scale same as above
PAY_6: Repayment status in April, 2005 (scale same as above)
BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)
BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)
BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)
BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)
BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)
BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)
PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)
PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)
PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)
PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)
PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)
PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)
default.payment.next.month: Default payment (1=yes, 0=no)

## Project Summary
Credit card default prediction is a process of using statistical and machine learning techniques to forecast the likelihood of a credit card holder defaulting on their payments. Defaulting occurs when a cardholder fails to make the minimum required payment on their credit card for a certain period, typically 180 days.

The prediction of credit card defaults is crucial for financial institutions, as it helps them assess the creditworthiness of applicants and manage the risk associated with extending credit. By accurately predicting the probability of default, lenders can make informed decisions regarding credit approvals, credit limits, interest rates, and collection strategies.

To predict credit card defaults, various features and data points are considered. These may include the cardholder's demographic information (age, gender, income), credit history (payment history, outstanding balances, credit utilization), employment details, and other variables. Machine learning algorithms are applied to historical data to identify patterns and build models that can predict future defaults.

Here we used techniques for credit card default prediction include logistic regression, K-Nearest Neighbour, support vector machines, Decision trees, random forests, and XGBoost models. These models are trained on a labeled dataset, where historical data contains both default and non-default instances. The models learn to recognize patterns and make predictions based on the input features.

Evaluation of credit card default prediction models is typically done using metrics such as accuracy, precision, recall, and area under the receiver operating characteristic curve (AUC-ROC). These metrics provide insights into the model's performance in correctly classifying defaults and non-defaults.

##  Conclusion
From all baseline model, Random forest classifier shows highest test accuracy and F1 score and ROC_AUC score.
After cross validation and hyperparameter tunning, XG Boost shows highest test accuracy score of 87.70% and ROC_AUC score is 0.879.
Using a Logistic Regression classifier, we can predict with 82.5% accuracy, whether a customer is likely to default next month.
Using a K-Nearest Neighbour classifier, we can predict with 85.80% accuracy, whether a customer is likely to default next month.
Using a Support Vector Machine classifier, we can predict with 86.70% accuracy, whether a customer is likely to default next month.
Using a Decision Tree classifier, we can predict with 84.00% accuracy, whether a customer is likely to default next month.
Using a Random Forest classifier, we can predict with 87.40% accuracy, whether a customer is likely to default next month.
Using a XGBOOST classifier, we can predict with 87.70% accuracy, whether a customer is likely to default next month.
By performing cross-validation and hyperparameter tuning, we can improve the performance and generalization ability of a machine learning model.

