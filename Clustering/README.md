# Clustering - Fish Species based on Spawning Temperature

Based on spawning temperature of 159 fish species in Ontario, we can implement a cluster analysis using either K-means approach or Hierarchical Clustering. Here I show the application with both methods: 

## Using K-means

Unsupervised learning approach (K-means) is applied to 159 fish species. Data was based on the [Ontario freswater Fishes life History database]
The goal of this algorithm is to find 3 groups in the data based on spawning temperature. 

[Ontario freswater Fishes life History database]: http://www.ontariofishes.ca/home.htm
 
The algorithm splits the data in three groups based on the distance feature. Each cluster centroid is marked with a blue circle. Results show fish species preference of spawning temperature.



<img src="https://github.com/alminagorta/MachineLearning/blob/master/Clustering/K-means.png" width=1200/>



## Using Hierarchical Clustering

Commonly displayed as dendogram and it is clustered by steps. At each step, the cluster that are most similar are joined into a single new cluster. For instance, in the dendogram presented below:

* The vertical axis represents the distance or dissimilarity between clusters
* The horizontal axis represents the index of each fish species (also presented in the scatter plot) 
* How to select the number of clusters? typically the approach is to set the horizontal-dashed line to cut the maximum distance vertically without intersecting a cluster. In our case should be three.
* In other cases the user can select the number cluster. In this case I selected to have 6 clusters. Note that the dashed horizontal line in the dendogram cut the six main clusters, which are also presented in the scatter plot below by different colors.


<img src="https://github.com/alminagorta/MachineLearning/blob/master/Clustering/Dendogram1.png" width=1200/>
<img src="https://github.com/alminagorta/MachineLearning/blob/master/Clustering/Scatter1.png" width=1200/>


## More Information: 

* To find the raw data please visit the [Ontario freswater Fishes life History database]  
* Python Code: "Analysis_Ontario_fishes_v1.py". Contact o.alminagorta@utoronto.ca





