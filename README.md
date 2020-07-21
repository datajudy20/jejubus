# jejubus  
### prediction the number of bus passengers on jeju island during rush hour
- **data description**
  - all boarding information is recorded as the bus get-on and get-off data for payments made through the bus card, but when you get off the bus, if you do not take the bus card, the record is empty.
Therefore, the number of people getting on and off is not the same and there may be some differences.
  - Each latitude and longitude is provided for the bus stop. If it is the same bus stop name, but there are cases where latitude and longitude are different. In this case, it is a bus stop across the street with the same name.
  - **data**: The number of people getting on and off for each bus stop for each day on the island of Jeju in September 2019, from 8:00 to 12:00.
In addition, the number of people getting on each bus stop during the rush hour (from 18:00 to 20:00) is recorded.
  - **bus_bts**: bus information is recorded for each bus card. This data is only available when the boarding time is between 6 am and 12 am.
#
- **1_start_data_exploration.ipynb** : The process of identifying and exploring data for the first time
- **2_make_final_dataset.ipynb** : Create new data by processing and adding variables from raw data
- **3_variable_correlatioin.ipynb** : Correlation between explanatory variables of data
- **4_response_variable_exploration.ipynb** : Exploring the relationship between response and explanatory variables in the data
- **5_gridsearchcv_randomforest_modeling.ipynb** : Generate a random forest regression model using a grid search method with cross-validation
#
###### ***final_presentation.pdf file is a document presenting data analysis results***
###### ***data sources are : https://dacon.io/competitions/official/229255/overview/***
###### ***This team project was conducted at the Dongguk University B.a.f Society.***
