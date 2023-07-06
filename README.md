# Trips clustering project based on Driver Behavior  

## Project Overview
This project aims to segment the trips in a transport company based on their drivers' driving behavior. The behavior is characterized by several features such as the number of trips per day, distance driven per day, average speed, hours driven, and the area they stop. Clustering is performed using the K-means algorithm. 

## Getting Started
### Prerequisites
You'll need to install the following libraries before running the code:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`


## Project Description
The project starts with some data cleaning and aggregation of all the trips,  and an exploratory data analysis (EDA) to understand the underlying data and its distributions. 

The data is also processed through Principal Component Analysis (PCA). PCA is a dimensionality reduction technique that helps visualize high-dimensional data, highlight relationships between variables, and make the data more tractable for machine learning algorithms.

Then, the project proceeds with K-means clustering implementation. We aim to have a reasonable number of clusters while minimizing distortion. We also attempt to achieve a high silhouette score and a high Calinski-Harabasz score, although we anticipate some overlap of clusters due to the nature of driver behaviors.

## Files
1. `driver_data.csv`: The raw data for a fake driver list
2. `trip_data (3).csv`: The raw data from a real transport company (anonymized)
3. `geotab_trips-clustering.ipynb`: the actual jupyter notebook file

## Results
Based on our analysis, we found that a 3 or 5-cluster solution provides the best balance between the three metrics (distortion, silhouette score, and Calinski-Harabasz score).

## Author
- Didier

## License
No license
