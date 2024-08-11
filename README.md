# Fraudulent Transaction Detection using Machine Learning
## Project Objective
This project centers on developing a robust fraud detection system leveraging decision tree algorithms. The primary objective is to predict fraudulent transactions based on historical transactional data, employing decision trees known for their interpretability and ability to capture complex relationships within the data.

## Anti-Money Laundering - Case Study:
Link : https://github.com/neharikajsh/Fraud_Detection/blob/main/AML_as_service-Case_Study.pdf
## Data Source :
https://www.kaggle.com/datasets/ealaxi/paysim1

## Data Columns:
step - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

1. **type** - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

2. **amount** - amount of the transaction in local currency.

3. **nameOrig** - customer who started the transaction

4. **oldbalanceOrg** - initial balance before the transaction

5. **newbalanceOrig** - new balance after the transaction.

6. **nameDest** - customer who is the recipient of the transaction

7. **oldbalanceDest** - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).

8. **newbalanceDest** - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).

9. **isFraud** - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

## Summary of Results:
Overall, the decision tree model showed robust performance with an accuracy of 96%, effectively distinguishing between fraudulent and non-fraudulent transactions. The results indicate its suitability for fraud detection tasks, providing confidence in its ability to detect fraudulent activities while minimizing false alarms. Further refinement could focus on optimizing false positive and false negative rates to enhance operational efficiency based on specific business needs.

The decision tree model emphasizes the importance of monitoring changes in account balances, transaction amounts, and specific transaction types to detect fraudulent transactions effectively. By focusing on these key features, financial institutions can enhance their fraud detection systems, promptly identifying and mitigating potential risks associated with fraudulent activities.

This approach underscores the significance of feature selection and analysis in developing robust fraud detection strategies, enabling proactive measures to safeguard financial transactions and uphold security standards.
