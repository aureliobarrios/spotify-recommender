# spotify-recommender

The goal of this project is to build an unsupervised learning algorithm on a dataset of unlabeled music data. This project aims to build and generate clusters which will then be used to recommend music for a hypothetical user. 

## 1. EDA 

In this notebook univariate, bivariate and multivariate exploratory analysis is performed. Relevant graphs are displayed to showcase data findings. These include interesting findings in the dataset, relationships between predictors and more.

## 2. Data Processing

In this notebook I clean and wrangle the original music dataset. This includes dropping null values, removing unnecessary columns, removing outliers and potentially fixing incorrectly formatted data. I also remove columns that have a strong correlation and linearity. This dataset is then transformed into a dataset with smaller dimensions using a dimensionality reduction technique known as principal component analysis.

## 3. Model Creation

In this final notebook a KMeans clustering algorithm is built using our pca dataset. The optimal number of clusters is determined first using techniques like the elbow method and silhouette method. I then test the clustering algorithm on never before seen data to get a better sense as to the nuances that the algorithm is picking up on. 
