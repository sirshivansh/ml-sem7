# EXPERIMENT 6: GRAPH-BASED CLUSTERING

### 1. Aim
To implement Graph-Based Clustering using Python libraries.

### 2. Resources Required
1. Dataset file.
2. Google Colab.
3. Python libraries.
4. Minimum 4 GB RAM.
5. Intel i5 processor or above.

### 3. Theory

**1. Graph-Based Clustering**

Graph-Based Clustering is a clustering technique used to group similar data points based on their relationships and connections.

- Data objects are represented as **nodes** in a graph.
- Connections between nodes represent relationships between them.
- A weight is assigned to each connection based on the distance or similarity between two data points.
- The main objective is to group similar data points together and separate dissimilar data points.

**2. Clustering**

Clustering is an unsupervised machine learning technique used to divide a dataset into different groups called clusters.

Data points within the same cluster are similar to each other, while data points in different clusters are dissimilar.

**3. K-Means Clustering**

K-Means is a popular unsupervised machine learning algorithm used to divide a dataset into K predefined clusters.

- It assigns each data point to the nearest cluster based on the distance from the cluster centroid.
- A centroid is the centre point of a cluster.

**4. Steps of K-Means Clustering**

1. Specify the number of clusters (K).
2. Randomly select K data points as initial centroids.
3. Calculate the distance between each data point and all centroids.
4. Assign each data point to its nearest centroid.
5. Calculate new centroids by taking the average of all data points in each cluster.
6. Repeat the process until the centroids stop changing.

**5. Advantages of Clustering**

1. Groups similar data points together.
2. Helps identify patterns in large datasets.
3. Easy to understand and implement.
4. Useful for data analysis and segmentation.

**6. Disadvantages of Clustering**

1. The number of clusters (K) must be specified in advance for K-Means.
2. Results may depend on the initial centroid selection.
3. It is sensitive to outliers.
4. It may not work well with clusters having irregular shapes.

### 4. Conclusion
Hence, we have successfully implemented Graph-Based Clustering using the K-Means algorithm with Python libraries.