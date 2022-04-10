# Cryptocurrencies Analysis
## Background: Accouintability Accounting
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Data Sources:
[CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist)

## Deliverables:

* Deliverable 1: Preprocessing the Data for PCA
* Deliverable 2: Reducing Data Dimensions Using PCA
* Deliverable 3: Clustering Cryptocurrencies Using K-means
* Deliverable 4: Visualizing Cryptocurrencies Results

### Deliverable 1: Preprocessing the Data for PCA
Processed data to fit t-SNE & k-Means.
### Instructions
#### Data Preparation
- Read crypto_data.csv into Pandas. The dataset was obtained from CryptoCompare.

- Discarded all cryptocurrencies that are not being traded.

- Removed all rows that have at least one null value.

- Filtered for cryptocurrencies that have been mined.

- Converted features with text values into numerical data.

- Standardized dataset so that columns that contain larger values do not unduly influence the outcome.
### Deliverable 2: Reducing Data Dimensions Using PCA
#### Dimensionality Reduction
- Performed dimensionality reduction with PCA. Preserved 90% of the explained variance in dimensionality reduction.

- Reduced the dataset dimensions with t-SNE.
### Deliverable 3: Clustering Cryptocurrencies Using K-means
#### Cluster Analysis with k-Means
- Created an elbow plot to identify the best number of clusters.
- Used Silhouette Score to determine optimum number of clusters.
- Used heat map to identify highly correlated variables.
### Deliverable 4: Visualizing Cryptocurrencies Results

#### Recommendation
Based on my findings, cryptocurrencies can be clustered together into 4 distinct groups. Cluster results are grouped into csv files in the Clusters folder for further analysis.

Given more time, I would analyze these clusters for segmentation trends, looking at the global average of total coins mined and total coin supply, data compared to class average for each column.