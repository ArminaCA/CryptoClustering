# Crypto Clustering

## Overview

The objective of the Crypto Clustering initiative is to employ unsupervised learning methods, particularly K-means clustering, to forecast whether cryptocurrencies are influenced by alterations in prices over either a 24-hour or 7-day period. Furthermore, the project delves into examining how dimensionality reduction through Principal Component Analysis (PCA) can influence the clustering outcomes.

## Procedure

1. Import and preprocess the dataset.
2. Normalize the data using StandardScaler.
3. Determine the optimal k-value using the elbow method.
4. Employ K-means to cluster cryptocurrencies with the original scaled data.
5. Apply Principal Component Analysis (PCA) to reduce the feature set to three principal components.
6. Identify the best k-value using the PCA-transformed data.
7. Cluster cryptocurrencies using K-means with the PCA-processed data.
8. Visualize and contrast the outcomes using hvPlot.

## Conclusion

The project assesses how reducing the number of features affects data clustering with K-means. By comparing the clustering outcomes between the original dataset and the PCA-processed data, we gain insights into how dimensionality reduction impacts the clustering procedure.

## Language and Libaries 

- Python
- pandas
- NumPy
- scikit-learn
- hvPlot
