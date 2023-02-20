# Project Description
This project explores the US arrest data that contains the number of arrests for various crimes per 100k residents for each state. The aim is to separate different states into clusters based on crime and urban population. The project involves the following steps:

## Data Cleaning Stage
There were no missing values in the data set, and all data types were correct. The only adjustment made was renaming the state column.

## Principal Component Analysis (PCA)
PCA was conducted to reduce the number of variables from four to three. PCA eliminated the correlations found in the original variables.

## Hierarchical Clustering
Based on a series of displayed dendograms, a model based on complete linkage and cityblock distance was chosen. The silhouette score was 0.35. The clusters were defined as follows:

* Cluster 0: has high rates for all crime types and also for the % urban population. This cluster likely contains states with lower socio-economic status regions, high in crime and urbanized areas. For example, New York and California.

* Cluster 1: also has a high % of urban population, but the rates for all crime types are medium. This cluster likely contains more well-off and urbanized states. For example, New Jersey and Washington.

* Cluster 2: has the lowest rates of all crimes and the lowest % of urban population. This cluster likely contains more rural and well-off states. For example, Maine and Vermont.

* Cluster 3: has the highest rates of murder and assault, but the % living in urban areas is on the lower end, and rape rates are medium. This cluster likely contains more rural states but with lower socio-economic status regions. For example, Louisiana and Alabama. It seems most states in this cluster are Southern states.

## KMeans Clustering
KMeans clustering was then performed on the same data. The silhouette score was 0.37. The cluster allocation in the KMeans model was similar to the hierarchical model:

* Cluster 0: almost entirely the same in both models.

* Clusters 1 and 2: similar; however, there was an overlap in those two clusters between the models.

* Cluster 3: almost the same in both models.

This project shows an approach to separating different states into clusters based on crime and urban population, which can provide insights for policy-makers and researchers alike.
