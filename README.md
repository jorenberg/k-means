# <i>k</i>-means® [![Apache License](https://img.shields.io/badge/license-Apache-blue.svg)](https://github.com/iamprabhat/k-means/blob/master/LICENSE)
<b><i>k</i>-means®:</b> <i>k</i>-means clustering in C++, Python, Ruby, and R.

## Definition
<i>k</i>-means clustering is a heuristic method of vector quantization, that is popular for cluster analysis in data mining.

The <i>k</i>-means algorithm is a type of unsupervised machine learning algorithm. It is a clustering algorithm that operates on n-dimensional data sets. The algorithm operates by choosing random centers in the data space, then fine-tuning the location of those centers by minimizing the sum of squared distances from the points of the group assigned to a particular center. It is an iterative algorithm, which alternately refines the position of the centers, then reassigns data points to the nearest centre, if necessary. The assignment of a data point to single center result in the formation of clusters.

### The <i>k</i>-Means: A Centroid-Based Technique
The <i>k</i>-means algorithm takes the input parameter, <i>k</i>, and partitions a set of n objects into <i>k</i> clusters so that the resulting intracluster similarity is high but the intercluster similarity is low. Cluster similarity is measured in regard to the <i>mean</i> value of the objects in a cluster, which can be viewed as the cluster’s <i>centroid or center of gravity</i>.

Suppose a data set, D, contains <i>n</i> objects in Euclidean space. Partitioning methods distribute the objects in D into <i>k</i> clusters, C<sub>1</sub>,..., C<sub>k</sub>, that is C<sub>i</sub> ⊂ D and C<sub>i</sub> ∩ C<sub>j</sub> = ø for (1≤ <i>i,j</i> ≤ <i>k</i>). An objective function is used to asses the partitioning quality so that objects within a cluster are similar to one another but dissimilar to objects in other clusters. This is the objective function aims for high intracluster similarity and low intercluster similarity.
