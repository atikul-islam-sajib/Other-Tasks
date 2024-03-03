
# Geospatial Clustering Project

## Overview

This project performs geospatial clustering on a dataset and visualizes the results. The clustering is based on sociodemographic and geospatial data to segment customers into distinct groups for targeted analysis.

## Results

The following figures show the clustering results on a map, with each cluster represented by a different color:

![Geospatial Data Visualization: Cluster 1]([path-to-image/cluster_1.png](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/geo-clustering/download.png))
*Figure 1: Clusters of geospatial data highlighting cluster 1.*

![Geospatial Data Visualization: Cluster 2](path-to-image/cluster_2.png)
*Figure 2: Clusters of geospatial data highlighting cluster 2.*

![Geospatial Data Visualization: Cluster 3](path-to-image/cluster_3.png)
*Figure 3: Clusters of geospatial data highlighting cluster 3.*

![Geospatial Data Visualization: Cluster 4](path-to-image/cluster_4.png)
*Figure 4: Clusters of geospatial data highlighting cluster 4.*

![Geospatial Data Visualization: Cluster 0](path-to-image/cluster_0.png)
*Figure 5: Clusters of geospatial data with an emphasis on cluster 0, indicating areas not included in clusters 1-4.*

Additionally, a Scree Plot was generated to determine the number of clusters:

![Scree Plot](path-to-image/scree_plot.png)
*Figure 6: Scree Plot used to determine the optimal number of clusters based on eigenvalues.*

## How to Run

1. Clone the repository:
   ```
   git clone https://github.com/atikul-islam-sajib/Other-Tasks.git
   ```
2. Change to the project directory:
   ```
   cd geo-clustering
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
4. Run the main script:
   ```
   python main.py
   ```

## Requirements

- Python 3.6 or higher
- Required Python libraries as listed in `requirements.txt`
