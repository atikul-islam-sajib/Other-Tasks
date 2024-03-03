
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

## Confusion metrics - after training
```sh
Confusion Matrix:
 [[ 77  10 122  25  51]
 [  0   2   0   1   0]
 [  7   0  27   0   1]
 [  0   0   0   8   2]
 [  7   0   0   0  15]]
````

## Classification report - after training 
```sh
Classification Report:
               precision    recall  f1-score   support

           0       0.85      0.27      0.41       285
           1       0.17      0.67      0.27         3
           2       0.18      0.77      0.29        35
           3       0.24      0.80      0.36        10
           4       0.22      0.68      0.33        22

    accuracy                           0.36       355
   macro avg       0.33      0.64      0.33       355
weighted avg       0.72      0.36      0.39       355
```


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
