# ML-Credit_Card_fraud_detection
Comparing results for Credit_Card_Fraud_Detection using IsolationForest, LocalOutlierFactor,RandomForest

You can upload dataset for this link https://www.kaggle.com/mlg-ulb/creditcardfraud

LocalOutlierFactor performs poorly with a precision of 0.02 for fraud transactions

IsolationForest has a precision of 0.28 for fraud transactions
But after oversampling this imbalanced dataset using SMOTE and using RandomForestClassifier over this oversampled dataset
this model gives a precision of 1.00 for fraud transactions on oversampled dataset and a precision of 0.80 on imbalanced dataset.
