# K-means Clustering
# Machine Learning algorithms are categorized into three main categories : Supervised , Unsupervised and reinforcement learning. In supervised learning,in the given data set you have your class label or a target variable present and In unsupervised learning, all you have is set of features,you don't know about your target variable or a class label.So, usinf this data set we try to identify the underlying structure in that data or we sometimes try to find the clusters in that data and we can make useful predictions out of it.
# 1. Start with K centroids by putting them at random place,say k=2
# 2. Compute distance of every point from centroid and cluster them accordingly.
# 3. Adjust centroids so that they become center of gravity for given cluster.
# 4. Again re-cluster every point based on their distance with centroid.
# 5. Again adjust the centroids.
# 6. Recompute clusters and repeat this till data points stop changing clusters.
# Elbow Method : To determine correct number of clusters (k), a technique called Elbow Method is used.
# In elbow method, you start with some k,say k=2,and we try to compute sum of square error.Sum of square error means you try to compute the distance of individual data points from the centroid,you square it and then you sum it up.Then repeat the same process for k=2,3,4,and so on,and once you have that number, you draw a plot and find the elbow point.
# As the number of clusters increases, sum of error decreases.At elbow point you get the good cluster number and use it for your data set.
# Now please go through the python code and data set,which is uploaded.
