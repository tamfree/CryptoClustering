# CryptoClustering

## Description

Classifying cryptocurrencies by price fluctuations

## Execution

### Dependnencies
Pandas
sklearn.cluster.KMeans
sklearn.preprocessing.StandardScaler

### Command

## Process

1. Ingest cryptocurrency pricing data using Pandas
1. Cleansing the raw input data was not needed because all rows contained non-null floats.
1. Normalize the features using sklearn.preprocessing.StandardScaler
1. Create clusers using sklearn.cluster.KMeans specifying the ideal k value.
    1. First using the original set of features
    1. Then again using a set of features modified using Princpal Compononent Analysis. In the real world, PCA would likely not be required for this amount of data.

## Lesson

Lesson 11 - Unsupervised Learning

Concepts covered:

* Using *Standard Scaling* to normalize data.
* Using *Principal Component Analysis (PCA)* to reduce the number of features requiring analysis to cluser the data

Defined as
z = (x - $\mu$) / $\sigma$
