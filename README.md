Loan
====

loan default optimization
Python code for Kaggle's Loan Default Prediction (learning about feature creation, extraction, cross validation and boosted models)

Improvements for future
No feature creation or cross validation was used in this script... another approach created features using an iteration of an operator (+, -, x, /) between two features and the operator (a-b)*c among three of the 'golden features' that were leaked during the competition.  Ensembling different models (log regs, different boosted models including svms) seemed to be extremely popular but computing power is an issue for me.

Preprocessing
f_regression was used for selection of features with high F-values  


Model 
GBM classifier(train data) --> GBM regression with features normalized and loss later transformed to log(loss) for predictions as there was a large distribution for loss

Download train and test data sets from kaggle put Loan Prediction.py in the same folder and run it




