# Anomaly-Detection-Using-K-means-Clustering

Anomaly Detection using K-means clustering is to detect the outlier points in the dataset that should not belong to any cluster.

K means clustering is dividing the given dataset into clusters based on the calculated cluster centroids. The datapoints are then assigned to the cluster with minimum distance
from the cluster centroid. The clustering is well suited for datasets with gaussian distribution. The optimum number of clusters for a dataset is calculated using the Silhouette coeffcient method.

After clustering, anomalies are identified by 
  1. The small clusters with less than a threshold (1% of total number of data points) 
  2. Isolation data points not belong to any cluster
  3. A data point belongs to a cluster with more than 2 standard deviations (i.e., 95% confidence).
