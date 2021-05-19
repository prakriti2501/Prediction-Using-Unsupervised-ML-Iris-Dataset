Prediction Using Unsupervised Machine Learning
By: Prakriti Arora

OBJECTIVE: From the given ‘Iris’ dataset, predict the optimum number of clusters
and represent it visually.


ALGORITHM USED - K-Means Algorithm

K-Means It is an iterative algorithm that divides the unlabeled dataset into k different clusters in such a way that each dataset belongs only one group that has similar properties.

Workflow behind Implemention of K-Means Clustering

1. Select the number K to decide the number of clusters.

2. Select random K points or centroids. (It can be other from the input dataset).

3. Assign each data point to their closest centroid, which will form the predefined K clusters.

4. Calculate the variance and place a new centroid of each cluster.

5. Repeat the third steps, which means reassign each datapoint to the new closest centroid of each cluster.

6. If any reassignment occurs, then go to step-4 else go to FINISH.

7. The model is ready.