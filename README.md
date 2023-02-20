# Final Capstone Project Using Unsupervised Learning

In this project I have worked with US arrest data. The data contains the number of arrests for various crimes per 100k residents for each US State.

1. Data Cleaning Stage

There were no missing values in the data set and all data types were correct. The only adjustment done was renaming of the State column

2. Principal Component Analysis (PCA)

PCA was conducted to reduce the number of variables from four to three. PCA eliminated the correlations that were found for original variables.

3. Hiararchical Clustering

Based on a series of displayed dendograms, a model based on complete linkage and cityblock distance was chosen.

The shiluette score was 0.35

The clusters seem to be as follows:
Cluster 0 has high rates for all crime types and also for the % urban population. This cluster likely contains states with lower socioeconomical status regions, high in crime and urbanised areas. For example New York and California.
Cluster 1 also has a high % of urban population but the rates for all crime types are medium. This cluster likely contains more well off and urbanised states. For example New Jersey and Washington.
Cluster 2 has the lowest rates of all crimes and the lowest % of urban population. This cluster likely contains more rural and well off states. For example Maine and Vermont.
Cluster 3 has highest rates of murder and assault but the % living in urban areas is on the lower end and rape rates are medium. This cluster likely contains more rural states but with lower socioeconomical status regions. For example Luisiana and Alabama. It seems most States in this cluster are Sauthern states.
