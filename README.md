# Credit Card Fraud Detector 

A variety of machine learning algorithms are used to detect credit card fraudulent transactions. Here, dataset which is downloaded from Kaggle.com, consists of 284,807 rows and 31 columns. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

Due to high number of features, strategy is made to reduce the feature by checking correlation of each feature to the target label 'Fraud'. Features which have strong correlation with target label are selected for further investigation. Furthermore, probability density function of the selected features are investigated for all target classes using Kernel Density Estimate plot. 

Dataset with reduced features is then split into training and test set with a ratio of 1:3 for test set. The training set is used to train the following classification model.
* K-Nearest Neighbor(KNN)
* Decision Tree
* Support Vector Machine
* Logistic Regression

The resulting models will be evaluated using the following evaluation parameters:
* Jaccard Index
* F1-score
* Log-Loss

Here, confusion matrix will be utilized to explain the performance of the algorithms. 

At last, conclusions and recommendations will be given based on the results and analysis.

Visit the following link to get a lite version of the report.

<a href="https://www.w3schools.com/">Visit W3Schools.com!</a>
