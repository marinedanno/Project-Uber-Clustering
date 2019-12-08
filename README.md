# Project-Uber-Clustering

## The objective 

The main idea was to cluster Uber pickups in order to define different zones in NY for Uber drivers. 

## The methods 

A kmeans clustering algorithm was used first. We found out that k = 4 was the best model. We could also plot the centroids on a map thanks to the folium package. This allowed us to clearly identify the zones.

Then we used a DBSCAN model to compare with the kmeans model. With DBSCAN we didn't have to choose the number of clusters. But it found a lot of noise. 
