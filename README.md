# CreditCardFraudDetectionML
Running classifiers to build a fraud predictor

Credit card fraud detection using Machine Learning models.

Logistic Regression
Random Forest
Decision Tree
Naive Bayes

Use dataset Synthectic financial that is available on kaggle. https://www.kaggle.com/ealaxi/paysim1
This is a sample of 1 row with headers explanation:
1,PAYMENT,1060.31,C429214117,1089.0,28.69,M1591654462,0.0,0.0,0,0 step - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation). type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.
amount - amount of the transaction in local currency.
nameOrig - customer who started the transaction oldbalanceOrg - initial balance before the transaction newbalanceOrig - new balance after the transaction nameDest - customer who is the recipient of the transaction oldbalanceDest - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants). newbalanceDest - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants). isFraud - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system. isFlaggedFraud - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.

For data preprocessing use Train test split and standard scaler.
and For evaluation USE Confusion matrix, accuracy, precision, recall, F1-Score.

Additional Reading: https://github.com/EdgarLopezPhD/PaySim
