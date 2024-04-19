# Brief Introduction

Objective of this project was to train a clustering-based model to extract top 50 words from each cluster from a json dataset having news articles of mixed topics including business, entertainment, politics, sports, technology, but without labels. 

The project involved performing dimensionality reduction and unsupervised learning over the dataset and then analyzing the most frequently occurring words of all the clusters.
K-Means Clustering, Principal Component Analysis algorithms were used.

# Details about the project

You are provided with a dataset “NewsArticles.json” having news articles of mixed topics including business, entertainment, politics, sports, technology, but without labels. 
You are required to make a clustering-based model. 
 
Carry out the following tasks:
 
Perform K-Means clustering on the above dataset and find the value of Sum of Squared Error (SSE)
Use PCA algorithm to reduce the dimension of the dataset (about 100) and then perform K-means clustering on the manipulated dataset and find the value of Sum of Squared Error (SSE)
Find the cluster having the highest value of count (before PCA). Also mention the value of count
Find the cluster having the highest value of count (after PCA). Also mention the value of count
Extract top 50 words from each cluster in both the cases and print the last word (50th word) from the cluster you think is of news articles related to the topic of entertainment (before PCA)
Extract top 50 words from each cluster in both the cases and print the last word (50th word) from the third cluster (after PCA)    
 
In both the above cases, use the number of clusters as 5 and compute Sum of Square Error within clusters.

Output Format:

Perform the above operations and write your output to a file named output.csv
output.csv should contain the answer to each question on consecutive rows.
