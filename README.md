# Machine Learning for Big Data

This repo contains some of the popular algorithms often used in Machine Learning when analyzing big data. There are a total of 9 algorithms/projects that were completed:

1. Friendship Recommendation
   1. This was used to practice Spark and get familiar with using PySpark.
2. A-priori algorithm
   1. Here the A-priori algorithm was implemented to find products which are frequently browsed together.
3. Alternating Least Square (ALS)
   1. In many real-world applications, it’s expensive to collect explicit rating data. However, it’s cheap to collect implicit feedback data such as clicks, page views, purchases and media streams at a large and fast scale. In this, the ALS algorithm was implemented to recommend music artists based on implicit data. 
4. K-means
   1. The k-means algorithm aims to partition a dataset into k clusters, to minimize the distance metric between each point, within the cluster. Here the k-means algorithm was implemented for 2 different distance metrics and 2 different initialization criteria.
5. PCA
   1. Principal Component Analysis (PCA) is a dimensionality reduction algorithm that represents the data matrix as a set of principal components that are orthogonal to each other. Here PCA was implemented to reconstruct pictures of faces in the PCA basis.
6. Louvain
   1. The Louvain Algorithm is commonly used for community detection in graphs which can be especially a good fit for graphs with a hierarchical structure.
7. Spectral Clustering
   1. In this problem, we explore (yet another) such partitioning method called “spectral clustering”. The name derives from the fact that it uses the spectrum of certain matrices (that is, the eigenvalues and eigenvectors derived from the graph and the key idea is to minimize cut. Mathematically, cut minimization is closely related to modularity maximization. Our goals in this problem are to derive a simple algorithm for spectral clustering, apply it on a dataset, and interpret the clustering results.
8. SVM
   1. Here the soft-margin SVM using different methods of gradient descent. The different methods of gradient descent include: 
      1. Batch Gradient Descent (BGD)
      2. Stochastic Gradient Descent (SGD)
      3. Mini-Batch Gradient Descent (MBGD)
9.  Data Streams
    1.  We are going to follow an algorithm for determining the approximate frequencies of the unique items in a data stream. We will specifically investigate how we can get a feasible approximation that uses less space than the naive solution but is still a good estimate of the actual frequencies. We will also experiment with a real stream dataset to empirically investigate our claims. This data stream has images of everything out there in the universe, ranging from stars, galaxies, asteroids, to all kinds of awesome exploding/moving objects. Your task is to determine the approximate frequencies of occurrences of different (unique) items in this data stream.