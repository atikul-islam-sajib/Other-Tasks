![Quality Gate Status](https://github.com/atikul-islam-sajib/Other-Tasks/blob/main/projects/Model-Drift/Screenshot%20(48).png)


## Excercise 1

- **Drift Factor**: Determines the magnitude of drift in data.
  - **Large Drift**: High `drift_factor`, resulting in significant data alterations.
  - **Small Drift**: Low `drift_factor`, causing minor data changes.
- **Impact on Model**:
  - Large drift leads to a substantial drop in model accuracy due to significant differences between training and test data.
  - Small drift has a minimal impact on model performance, indicating the model's resilience to slight data variations
 

## Excercise 2:

###### 1. Concept Drift - **Example**: A sentiment analysis model trained on 2000s movie reviews begins to perform badly on current reviews due to linguistic changes and new slang.


[Link of the dataset](https://www.kaggle.com/datasets/abhi8923shriv/sentiment-analysis-dataset).


###### 2. Data Drift - **Example**: A model predicting property prices based on location and size loses accuracy as the dataset ages and no longer reflects current market trends.

[Link of the dataset]( https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

###### 3. Seasonal Drift - **Example**: An electricity demand forecasting model may not accurately predict unexpected heatwaves or cold snaps due to seasonal variability.

[Link of the dataset](https://www.kaggle.com/code/manualrg/daily-electricity-demand-forecast-machine-learning).


###### 4. Label Drift (Example) The nature of spam emails evolves over time, rendering prior categorization less

[Link of the dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).

###### 5. Feature Drift (Example): A predictive maintenance model for industrial equipment becomes less predictive over time as the significance of specific sensor signals shifts due to equipment upgrades or changes in the manufacturing process.

