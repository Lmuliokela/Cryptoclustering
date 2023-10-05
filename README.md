# Crypto Clustering

---

## Overview

In this challenge, the requirement was to use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

---

## Dependencies

import pandas as pd

import hvplot.pandas

from sklearn.cluster import KMeans

from sklearn.decomposition import PCA

from sklearn.preprocessing import StandardScaler

---

## Analysis

- Load the data into a Pandas DataFrame
- Prepare the Data
- Use the `StandardScaler()` module from scikit-learn to normalize the data from the CSV file
- Prepare the Data
- Cluster Cryptocurrencies with K-means Using the Original Data
- Optimize Clusters with Principal Component Analysis
- Find the Best Value for k Using the PCA Data
- Cluster Cryptocurrencies with K-means Using the PCA Data
- Visualize and Compare the Results
  
