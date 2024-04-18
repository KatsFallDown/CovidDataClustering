**This work is a project to study clustering algorithms.**

The paper discusses the k-means and c-means algorithms. 
These algorithms are similar to each other, but have differences. The result of the project can be called a comparison of algorithms

## Results:

### k-means algorithm:
- Allows you to work with unlabeled data, that is, it does not require the presence of categories or classes in the training data set.
- Uses an approach based on minimizing the total square deviations between points and centroids of clusters.
- Requires preliminary setting of the number of clusters.
- The optimal number of clusters can be determined using various methods such as the elbow method or the silhouette index.

### c-means algorithm:
- Also a clustering algorithm using the “nearest neighbors” approach.
- Uses the concept of a membership function that allows each data point to have a fuzzy membership in each cluster.
- Requires setting the number of clusters in advance.
- More flexible than k-means as it allows points to belong to multiple clusters with varying degrees of membership.

## Сonclusions:
During the work, it was discovered that the choice between k-means and c-means should be based on the nature of the data and the problem to be solved. 
If the goal is to separate data points into rigid clusters, then k-means seems to be a more appropriate choice. 
In cases where having fuzzy memberships makes sense, c-means may be a more rational solution.

Both algorithms have their drawbacks, such as sensitivity to outliers and dependence on the initial position of the centroids. 
Therefore, before applying these algorithms, it is necessary to analyze the data and use additional methods to improve the efficiency of clustering.
