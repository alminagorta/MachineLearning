# Clustering - Fish Species based on Spawning Temperature

## Using K-means

Unsupervised learning approach (K-means) is applied to 159 fish species. Data was based on the [Ontario freswater Fishes life History database]
The goal of this algorithm is to find 3 groups in the data based on spawning temperature. 

[Ontario freswater Fishes life History database]: http://www.ontariofishes.ca/home.htm
 
The algorithm splits the data in three groups based on the distance feature. Each cluster centroid is marked with a blue circle. Results show fish species preference of spawning temperature.



<img src="https://github.com/alminagorta/MachineLearning/blob/master/Clustering/K-means.png" width=1200/>



## Using Hierarchical Clustering. Commonly displayed as dendogram. In the dendogram presented below:

* The vertical axis represents the distance or dissimilarity between clusters
* The horizontal axis represents the objects
* At each step, the cluster that are most similar are joined into a single new cluster 
* The dashed horizontal line cut the three main clusters. Typically this line es selected considering the maximum distance vertically without intersecting a cluster.If you want to learn more about dendograms, see these resources:



Python Code: "Analysis_Ontario_fishes_v1.py".  More information at o.alminagorta@utoronto.ca



## Data Source- 159 fish data parameters:
To find the raw data:
* http://www.ontariofishes.ca/home.htm

## More Information: 
Please visit the [Ontario freswater Fishes life History database] or contact o.alminagorta@utoronto.ca


