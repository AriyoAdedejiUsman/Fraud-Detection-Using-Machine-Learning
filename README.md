# Fraud Detection Using Machine Learning

This project applies machine learning techniques to detect fraudulent transactions within a financial dataset. The model achieves an impressive accuracy of **99.97%**.

## Dataset
The dataset contains the following features:
- **step**: Time unit of the transaction.
- **type**: Transaction type (e.g., CASH_OUT, PAYMENT).
- **amount**: Transaction amount.
- **oldbalanceOrg/newbalanceOrg**: Sender's balances before and after the transaction.
- **oldbalanceDest/newbalanceDest**: Receiver's balances before and after the transaction.
- **isFraud**: Indicator of fraud (1 for fraud, 0 otherwise).
- **isFlaggedFraud**: Indicator if the transaction was flagged as fraud.

## Steps
1. **Data Preprocessing**: Cleaned the data and mapped transaction types to numeric values.
2. **Feature Engineering**: Derived meaningful features for better prediction.
3. **Modeling**: Used a machine learning model to predict fraud.

## Results
- **Accuracy**: 99.97%

## Tools
- **Python**: pandas, sklearn, seaborn, matplotlib.

## Conclusion
The project demonstrates the potential of machine learning in detecting fraudulent transactions effectively.

Feel free to check out the full code in this repository and share your feedback!

