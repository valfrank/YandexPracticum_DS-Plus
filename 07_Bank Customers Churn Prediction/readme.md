# Bank Customers Churn Prediction

## Project description
Banking marketers figured it was cheaper to keep current customers than to attract new ones.
It is necessary to predict whether the client will leave the bank in the near future or not. We are provided with historical data on customer behavior and termination of agreements with the bank.

**Aim** - build the model for the classification problem with the largest possible F1-score (min 0.59).

## Data
Data: [kaggle](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

*Features*
- RowNumber - row index in data
- CustomerId - unique customer identifier
- Surname - surname
- CreditScore - credit rating
- Geography - country of residence gender
- Age - age
- Tenure - how many years a person has been a bank client
- Balance - account balance
- NumOfProducts - the number of bank products used by the client
- HasCrCard - the presence of a credit card
- IsActiveMember - client activity
- EstimatedSalary - estimated salary

*Target*
- Exited - the fact that the client left

## Resume
- Conducted data preparation
- Train three models (DecisionTreeClassifier, RandomForestClassifier, LogisticRegression)
- The most accurate was the random forest model with the metric F1=0.58

## Skills and tools 
- python
- pandas
- mathplotlib
- sklearn
- GridSearchCV
- StandartScaler
- Imbalanced data
- Regression metrics: F1, roc-auc score, roc curve
