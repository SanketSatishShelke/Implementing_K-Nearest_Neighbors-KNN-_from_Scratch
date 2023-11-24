# Implementing_K-Nearest_Neighbors-KNN-_from_Scratch

In K-Nearest Neighbors there is no learning required as the model stores the entire dataset and classifies data points based on the points that are similar to it. It makes predictions based on the training data only.
Lets assume there are two classes of data (Red and Green) and we are given a new data point (black) and asked to specify which class does this new datapoint belongs to?
Well, KNN drives on the notion that similar items tend to be closer in groups. So it is quite evident that the new data point is closer to the red group and hence the algorithm will classify this point as Red.

However there are multiple ways to calculate distance in KNN as mentioned below:
1. Manhattan Method
2. Euclidean Method
3. Minkowski Method
4. Mahalanobis distance

In this code we will be using Euclidean distance to calculate the distance of a new data point from each point in our training dataset.
