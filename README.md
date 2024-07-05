# Hierarchical_Clustering_ML
A Hierarchical clustering method works via grouping data into a tree of clusters. Hierarchical clustering begins by treating every data point as a separate cluster. Then, it repeatedly executes the subsequent steps:

Identify the 2 clusters which can be closest together, and
Merge the 2 maximum comparable clusters. We need to continue these steps until all the clusters are merged together.
In Hierarchical Clustering, the aim is to produce a hierarchical series of nested clusters. A diagram called Dendrogram (A Dendrogram is a tree-like diagram that statistics the sequences of merges or splits) graphically represents this hierarchy and is an inverted tree that describes the order in which factors are merged (bottom-up view) or clusters are broken up (top-down view).
Hierarchical clustering has several advantages over other clustering methods
The ability to handle non-convex clusters and clusters of different sizes and densities.
The ability to handle missing data and noisy data.
The ability to reveal the hierarchical structure of the data, which can be useful for understanding the relationships among the clusters.
Drawbacks of Hierarchical Clustering
The need for a criterion to stop the clustering process and determine the final number of clusters.
The computational cost and memory requirements of the method can be high, especially for large datasets.
The results can be sensitive to the initial conditions, linkage criterion, and distance metric used.


Database: Iris Dataset
