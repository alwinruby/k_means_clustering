# K-Means Clustering


This is a simple, however effective unsupervised clustering algorithm.  
It attempts to partition the dataset into K pre-defined clusters where each data point belongs to only one group.

There are three steps

1. Initialisation
2. Calculate distance and assignment
3. Move the centres


To process the learning data, the K-means algorithm in data mining starts with a first group of randomly selected centroids, which are used as the beginning points for every cluster, and then performs iterative (repetitive) calculations to optimize the positions of the centroids

It halts creating and optimizing clusters when either:

    The centroids have stabilized — there is no change in their values because the clustering has been successful.

    The defined number of iterations has been achieved.

In general.

    Step 1: Import libraries
    Step 2: Generate random data
    Step 3: Use Scikit-Learn
    Step 4: Finding the centroid
    Step 5: Testing the algorithm

K-means clustering is an extensively used technique for data cluster analysis.

More specific

        Step-1: Select the number K to decide the number of clusters.

        Step-2: Select random K points or centroids. (It can be other from the input dataset).

        Step-3: Assign each data point to their closest centroid, which will form the predefined K clusters.

        Step-4: Calculate the variance and place a new centroid of each cluster.

        Step-5: Repeat the third steps, which means reassign each datapoint to the new closest centroid of each cluster.

        Step-6: If any reassignment occurs, then go to step-4 else go to FINISH.

        Step-7: The model is ready.


Or

        Step-1: Data pre-processing Step

        Step-2: Finding the optimal number of clusters using the elbow method

        Step- 3: Training the K-means algorithm on the training dataset

        Step-4: Visualizing the Clusters



In a nutshell, k-means clustering tries to minimise the distances between the observations that belong to a cluster and maximise the distance between the different clusters. In that way, we have cohesion between the observations that belong to a group, while observations that belong to a different group are kept further apart.
