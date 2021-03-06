# ML-Random-Forest
Random forests is a supervised learning algorithm. It can be used both for classification and regression. It is also the most flexible and easy to use algorithm. A forest is comprised of trees. It is said that the more trees it has, the more robust a forest is. Random forests creates decision trees on randomly selected data samples, gets prediction from each tree and selects the best solution by means of voting. It also provides a pretty good indicator of the feature importance.

In a classification problem, each tree votes and the most popular class is chosen as the final result. In the case of regression, the average of all the tree outputs is considered as the final result. It is simpler and more powerful compared to the other non-linear classification algorithms.

How does the algorithm work?
It works in four steps:
1. Select random samples from a given dataset.
2. Construct a decision tree for each sample and get a prediction result from each decision tree.
3. Perform a vote for each predicted result.
4. Select the prediction result with the most votes as the final prediction.


### Advantages:
1. Random forests is considered as a highly accurate and robust method because of the number of decision trees participating in the process.
2. It does not suffer from the overfitting problem. The main reason is that it takes the average of all the predictions, which cancels out the biases.
3. The algorithm can be used in both classification and regression problems.
4. Random forests can also handle missing values. There are two ways to handle these: using median values to replace continuous variables, and computing the proximity-weighted average of missing values.
5. You can get the relative feature importance, which helps in selecting the most contributing features for the classifier.

### Disadvantages:
1. Random forests is slow in generating predictions because it has multiple decision trees. Whenever it makes a prediction, all the trees in the forest have to make a prediction for the same given input and then perform voting on it. This whole process is time-consuming.
2. The model is difficult to interpret compared to a decision tree, where you can easily make a decision by following the path in the tree.

### Application of Random Forest
1. Reomote sensing
2. Object detection
multiclass object dection is done using random forest algorithm,provide better dection in complicated environments
3. Kinect
random forest is used in a game console called kinect

### WHY RANDOM FOREST
1. No overfitting 
use of multiple trees reduce the risk of overfitting.Training time is less
2. High accuracy
runs efficiently on large database 
for large data, it produces highly accurate predictions
3. Estimates missing data
Random forest can maintain accuracy when a large proportion of data is missing