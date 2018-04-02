# Clustering 4 Ever  [ ![Download](https://api.bintray.com/packages/clustering4ever/Clustering4Ever/clustering4ever/images/download.svg) ](https://bintray.com/clustering4ever/Clustering4Ever/clustering4ever/_latestVersion)

Welcome to the LIPN Big Data Clustering Library gathering algorithms and quality indexes.

You will find additional contents about clustering algorithms [here](https://github.com/PhDStudentsP13/Clustering).

## [Documentation](http://www.beckgael.fr/doc/clustering4ever/)

## Include it in your project

Add `"clustering4ever" % "clustering4ever_2.11" % "0.1.27"` to your `libraryDependencies` in your build.sbt.
You can also take [specifics parts](https://bintray.com/clustering4ever/Clustering4Ever) :
* core [ ![Download](https://api.bintray.com/packages/clustering4ever/Clustering4Ever/core/images/download.svg) ](https://bintray.com/clustering4ever/Clustering4Ever/core/_latestVersion)
* clusteringscala [ ![Download](https://api.bintray.com/packages/clustering4ever/Clustering4Ever/clusteringscala/images/download.svg) ](https://bintray.com/clustering4ever/Clustering4Ever/clusteringscala/_latestVersion)
* clusteringspark[ ![Download](https://api.bintray.com/packages/clustering4ever/Clustering4Ever/clusteringspark/images/download.svg) ](https://bintray.com/clustering4ever/Clustering4Ever/clusteringspark/_latestVersion)

## Distributed algorithms, through Spark

### Clustering algorithms

#### Scalar data

##### Batch
* _K_-Means
* Self Organizing Maps
* [Mean Shift](https://github.com/beckgael/Mean-Shift-LSH)
  * Complexity
    * Initial complexity **O(n<sup>2</sup>)**
    * Improved complexity **O(n)** under some conditions

##### Streaming
* [GStream](https://github.com/Spark-clustering-notebook/G-stream)

### Binary data
* _K_-Modes

### Mixed data
* Self Organizing Maps
  * Mixed topological Map

### Preprocessing algorithms
* Gradient ascent
* Feature selection

## Pure Scala algorithms

### Clustering algorithms

#### Scalar data
* [Jenks Natural Breaks](https://en.wikipedia.org/wiki/Jenks_natural_breaks_optimization), a mono dimensionnal clustering
* [_K_-Means](clustering/scala/src/main/scala/K-Means/README.md), a _K_-Means implementation allowing the choice of the dissimilarity measure.

#### Binary data
* _K_-Modes

## [Quality Indexes](Documentation/doc/QualityIndexes.md)

#### External indexes
* Mutual Information (scala & spark)
* Normalized Mutual Information (scala & spark)

#### Internal indexes
* Davies Bouldin (scala)
* Silhouette (scala)


## [SparkNotebook](https://github.com/spark-notebook/spark-notebook)
Basic usages of implemented algorithms are exposed with SparkNotebooks under [SparkNotebooks](SparkNotebooks) directory.