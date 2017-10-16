# Unsupervised Learning Applied to Supply Chain Carriers

## Introduction
Machine learning is transforming supply chain visibility in new and creative ways.  Semi-supervised and unsupervised approaches provide new visualizing methods, processes for optimization, statistical analysis, and information retrieval products. This paper explores historical carrier performance data through principal component analysis and k-means clustering.  Through this form of unsupervised learning, a new approach towards ranking carriers is achieved beyond traditional lowest cost metrics. These insights and others have significant savings opportunities for clients as well as the potential to improve supply chain optimization and visibility. 

## Hypothesis
Among the many reasons clustering can prove a valuable tool for supply chain companies, here are a few reasons:
(1) Clustering carriers allows companies to efficiently determine which carriers are communicating (or not communicating) they type of transit related data to the their clients. 
2) Clustering carriers based on service level gives companies a new ranking metric beyond cost as a metric for of evaluating whether or not to use a specific carrier
(3) Clustering allows companies to categorize new carriers as they are added from new client accounts.

## Data
From a privately held company

## Methods
(1) Principal Component Analysis
(2) K-Means clustering

## Results
Dimensionality reduction through principal component analysis and k-means clustering yielded three distinctive carrier groups.  With nearly 45 transit related features per carrier, PCA proved a valuable tool in capturing relevant carrier performance features that allowed for later clustering to separate the carriers into identifiable groups.  After multiple iterations of various values for k, an optimum at k=3 was found based on sum of squared errors (Fig. 4) a silhouette coefficient score of approximately .55.

Among the three clusters, the degree of communication is as follows: cluster 2 contained highly communicative carriers who regularly sent transit status updates, weather delays, mechanical delays, transit exceptions, among other things, cluster 1 contained a mixture of carriers who communicated infrequently or not at all, and cluster 0 contained carriers who transmitted virtually no information at all.  For brevity, the three clusters can be referenced as (Cluster 2) Highly communicative (Cluster 1) Moderately-low communicative (Cluster 0) Uncommunicative.

This ranking tool based on performance clustering could be price engine to provide clients with the highest peforming carriers based on service level at the lowest cost. 
