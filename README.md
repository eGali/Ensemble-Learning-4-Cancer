Using ensemble learning to predict if features result in malignant cancer or a benign tumor.

I am using a dataset from the UCI website.
https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(original)

First method of approach is decision tree.

Second method is implementing a manual method of bagging. I create 19 decision trees from the original dataset by 
performing bagging with replacement and finally voting at the end.

Third, fourth, and fifth methods were bagging, adaboost, and random forest. These were done using the built in scikit-learn algorithms. 

Manual bagging method yielded the same result as the scikit-learn bagging algoithm.

Best result was random forest with accuracy of 95%

