###TASK 2 : K-MEANS

![image](https://github.com/user-attachments/assets/9829ec96-4323-4b34-b707-ca01e17121ff)

K-means is one of the unsupervised learning algorithms and is commonly used for clustering problems. This algorithm is used to partition data into K clusters, where each cluster consists of data points that are similar to each other.

##### How Does K-means Work?
* Initial Cluster Centers: First, K random centroids (cluster centers) are selected. These centroids serve as the starting points for the clusters.

* Assigning Data Points to Clusters: Each data point is assigned to the nearest centroid. Every data point is assigned to the cluster whose centroid is closest.

* Updating Centroids: For each cluster, a new centroid is calculated by taking the average (or mean) of all the data points in that cluster.

* Repeat: Steps 2 and 3 are repeated until the centroids no longer change, or after a predetermined number of iterations. This indicates that the algorithm has converged.

##### When Is K-means Used?
* Clustering: It is used to uncover the natural groups in data. For example, segmenting customers based on their shopping behaviors.

* Market Segmentation: Businesses can use K-means to group customers into segments with similar needs, making marketing strategies more effective.

* Feature Engineering: In large datasets, K-means can be used to divide the data into more meaningful parts for further analysis.

* Anomaly Detection: If a data point does not belong to any cluster (i.e., it is far from all centroids), it can be considered an anomaly. This is useful in fraud detection, for example.

* Image Compression: K-means can be used to reduce the number of colors in an image by grouping similar colors together.

##### Advantages of K-means:
* Simple and Fast: The algorithm is relatively fast and easy to understand.

* Efficient: K-means works well on large datasets.

* Versatile: It can work with many different types of data, but it performs best with numerical data.

##### Disadvantages of K-means:
* Predefined K Value: You need to specify the number of clusters (K) beforehand, which can sometimes be difficult.

* Sensitive to Initial Points: The algorithm is sensitive to the initial choice of centroids. Different initializations can lead to different results.

* Assumption of Circular Clusters: K-means assumes that the clusters are roughly spherical in shape. If the data does not follow this structure, K-means may not perform well.

* Outliers: K-means can be heavily influenced by outliers because they affect the calculation of centroids.

##### When K-means Should Not Be Used?
* Complexly Shaped Clusters: K-means assumes the clusters are spherical or circular, so if your data has complex cluster shapes, K-means may not give good results. In such cases, algorithms like DBSCAN might be more appropriate.

* Presence of Outliers: If the dataset contains many outliers, K-means may perform poorly, as outliers will affect the centroids. Other algorithms like DBSCAN can handle outliers better.

##### K-means and Hyperparameter Selection:
The most important parameter for K-means is K (the number of clusters). To select the optimal K, some techniques can be used:

* Elbow Method: By plotting the total sum of squared errors (inertia) for different values of K, you can look for the "elbow" point on the graph. The K value at this point is often considered the optimal choice.

* Silhouette Score: This metric measures how well-separated the clusters are. A high silhouette score indicates well-separated clusters.

##### Conclusion:
K-means is a powerful algorithm for identifying groups of similar data points in your dataset. However, to obtain the best results, it's important to consider the appropriate data structure and choose the right K value.















Dataset: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
