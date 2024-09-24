# Clustering Analysis of Cardiac Arrest Data

## Project Overview

This project focuses on performing clustering analysis on a cardiac arrest dataset to identify patterns and group similar cases. The analysis includes data preprocessing steps, the application of both hierarchical and K-means clustering techniques, and evaluation of their performance.

## Key Features

- **Imported File**: Loaded the cardiac arrest dataset for analysis.
- **Checked for Null Values**: Identified and handled missing values in the dataset.
- **Pair Plot Visualization**: Created a pair plot between the 'radius_mean' and 'texture_mean' columns, segmented by diagnosis.
- **Feature Selection**: Selected 'radius_mean' and 'texture_mean' as features for clustering and created a new dataset.
- **Data Scaling**: Applied standard scaling to normalize feature values in the new dataset.
- **Hierarchical Clustering**: Displayed a dendrogram using Scipy to visualize hierarchical clustering.
- **Agglomerative Clustering**: Applied Agglomerative Clustering with 2 clusters, predicted the cluster labels, and created a column for these labels.
- **Label Analysis**: Checked and plotted the count of each label.
- **Silhouette Score**: Evaluated clustering quality using the silhouette score.
- **K-Means Clustering**: Applied K-means clustering with 2 clusters, checked the WCSS score (94%), and experimented with different numbers of clusters (1 to 10) to determine the optimal number.
- **Final K-Means Clustering**: Applied K-means with the best number of clusters based on the WCSS score and created a column for cluster labels.

## Why This Project?

This project demonstrates a comprehensive approach to clustering analysis, including data preprocessing, feature selection, and the application of both hierarchical and K-means clustering techniques. By comparing different clustering methods and evaluating their performance, the project provides insights into effectively segmenting data and interpreting clustering results.

## What You Will Learn

- Handling and preprocessing data for clustering tasks.
- Visualizing data relationships using pair plots.
- Applying and evaluating hierarchical and K-means clustering techniques.
- Selecting the optimal number of clusters based on WCSS and silhouette scores.
- Gaining practical insights into clustering real-world datasets for pattern recognition.

## Conclusion

The analysis of the cardiac arrest dataset using hierarchical and K-means clustering techniques revealed valuable insights into data segmentation. Hierarchical clustering provided a dendrogram for visualizing cluster relationships, while K-means clustering, evaluated through WCSS and silhouette scores, demonstrated effective cluster identification. This project highlights the importance of preprocessing, feature selection, and methodical evaluation in clustering analysis.
