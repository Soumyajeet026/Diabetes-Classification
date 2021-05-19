# Diabetes-Classification
The dataset is 'diabetes.csv'.
At first the attributes were scaled as their range was different.
Then KNN was fitted with 5 fold cross validation and number of neighbours as 10 to get the best accuracy.
Then in the same way Multi-Layer Perceptron was fitted.
As 'linear' kernel was better than 'rbf' so it was taken during SVC.
Then the mean accuracy was calculated to understand which method shows the best accuracy with respect to 'cross_val_accuracy'.
And it was found out that SVC with 'linear' kernel was showing the best result 
