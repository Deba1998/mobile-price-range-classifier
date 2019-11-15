# mobile-price-range-classifier

we classify different mobiles into different price range based on its specifications


Differnt price ranges are 0,1,2,3


We have used different models for classification and find that svm produces the best accuracy for this prediction 


The differnt accuracies for different models are as follows

SVM=97.18%

NAIVE BAYES= 80.62%

DECISION TREE=85.88%


RANDOM FOREST=88%(after applying grid search to modify the accuracy)

We have calculated differnt accuracies by taking mean of the results obtained from k-fold cross validation and improving the accuracies by applying grid search

As the x matrix consists of many features we have reduced the  dimensions using dimesionality techniques LDA and save it modelin 2-d and plot the graph for visualization

The initial model is saved in model.py

confusion matrix for model.py is:-

![Screenshot (88)](https://user-images.githubusercontent.com/49706281/68924163-19616400-07a6-11ea-9392-e7592fcd8c77.png)


confusion matrix for model in 2-d is:-

![Screenshot (89)](https://user-images.githubusercontent.com/49706281/68924403-c6d47780-07a6-11ea-986f-713de3941269.png)

The graph for training set for model in 2-d is:-



the graph for test set for model in 2-d is :-

