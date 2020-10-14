# SVM-on-bank-dataset
dataset=https://www.kaggle.com/henriqueyamahata/bank-marketing/home
# svm
https://github.com/data2450/ML-support-vector-machine
# aim of the project
The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. **The classification goal is to predict if the client will subscribe a term deposit (variable y).**

Data Set Information:
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.
# eda on the dataset
there were no missing values.catgorical features were handled by some feature engneering ,one-hot encoding for nominal catgorical varibles and label encoding for ordinal

standardized numeric variables only,with **standared scaler

used Scikit-Learn's **GridSearchCV** function to conduct model selection.

The prediction accuracy on the evaluation set is 90.0%
