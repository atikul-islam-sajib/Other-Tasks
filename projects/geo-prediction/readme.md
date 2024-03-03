
# Geospatial Prediction Project

## Overview

This project performs geospatial clustering on a dataset and visualizes the results. The clustering is based on sociodemographic and geospatial data to segment customers into distinct groups for targeted analysis.

## Results

The following figures show the clustering results on a map, with each cluster represented by a different color:

*Figure 1: Clusters of geospatial data highlighting cluster 1.*
![Geospatial Data Visualization: Cluster 1](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/geo-prediction/2.png)

*Figure 2: Clusters of geospatial data highlighting cluster 2.*
![Geospatial Data Visualization: Cluster 2](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/geo-prediction/3.png)

*Figure 3: Clusters of geospatial data highlighting cluster 3.*
![Geospatial Data Visualization: Cluster 3](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/geo-prediction/4.png)

*Figure 4: Clusters of geospatial data highlighting cluster 4.*
![Geospatial Data Visualization: Cluster 4](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/geo-prediction/5.png)


*Figure 0: Clusters of geospatial data with an emphasis on cluster 0, indicating areas not included in clusters 1-4.*
![Geospatial Data Visualization: Cluster 0](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/geo-prediction/1.png)

Additionally, a Scree Plot was generated to determine the number of clusters:
![Scree Plot](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/geo-prediction/-1.png)

Geo-Prediction of new customers' based on calculated geo-segments:

![Plot 1](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/geo-prediction/greater_0.75.png)
![Plot 2](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/geo-prediction/same_1.png)
![Plot 3](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/geo-prediction/same_2.png)
![Plot 4](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/geo-prediction/same_4.png)


## Requirements

- Python 3.6 or higher
- Required Python libraries as listed in `requirements.txt`

## How to Run In Vs code
1. Clone the repository:
   ```
   git clone https://github.com/atikul-islam-sajib/Other-Tasks.git
   ```
2. Install the requirements.txt
   ```
   pip install -r requirements.txt
   ```
3. Run the main.py file and wait for a while to do the cluster
   ```
   python main.py
   ```

## How to Run In Notebook

1. Clone the repository:
   ```
   git clone https://github.com/atikul-islam-sajib/Other-Tasks.git
   ```
2. Change to the project directory:
   ```
   cd geo-prediction
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
4. Run the main script:
   ```
   %run main.py
   ```

## User's Guideance Notebook
visit here [Notebook run ](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/geo-prediction/geo_prediction.ipynb).
