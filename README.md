# Predict-Network-Attack
# HACKEREARTH
Accuracy score 0.7774%
Data Description
You are given three files to download: train, test and samplesubmission. The data contains anonymised set of features. Train data has 169307 rows and test data has 91166.

Variable	Description
connection_id	unique id
cont_x	numeric features
cat_x	categorical features
target	target variable (0, 1, 2 are attack types)
Submission
A participant has to submit a csv file with connection_id and targets as prediction labels. Check the sample submission file for reference. Also, share your source code.

connection_id	target
cxcon_2	2
cxcon_5	0
cxcon_8	0
cxcon_11	1
cxcon_14	0
Evaluation Metric
Submission will be evaluated based on multi-classification accuracy metric.

Algorithm Used
Used support vector classifier to solve the problem with the best accuracy of 0.7774%.
other models were also used for the prediction but it has low accuracy.
