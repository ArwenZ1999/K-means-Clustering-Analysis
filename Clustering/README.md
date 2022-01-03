K-means is one of the most commonly used clustering analysis algorithm. This notebook apply the K-means functions to synthetic datasets in order to understand its behaviour and how to use a cluster validity index to decide the proper number of clusters underlying a data set.<br/>
Using data in the `Data` folder
##Part1. Implementation of the partition funcion
This part visualises initial partitions and final partitions, and use F-ratio to decide the optimal value for k
##Part2. Spectral Clustring Analysis
This part implement the asymmetric normalised spectral clustering algorithm.
##Part 3. Hierarchical Clustering Analysis
This part use Euclidean distance to produce the initial distance matrix and further apply the built-in function, scipy.cluster.hierarchy with three different cluster-distance metrics3:<br/>
1. single-linkage,<br/>
2. complete-linkage <br/>
3. group-average, 
##Part4. Ensemble Clustering Analysis
Implementation of ensemble clustering analysis and parameter tunning

