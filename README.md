# PRO_MTL_MTECH_PROJECT

## Abstract
In the current ridesharing scenario, finding a compatible passenger is highly challenging and largely dependent on chance. Existing algorithms prioritize the shortest route without considering future requests or traffic conditions, which reduces the likelihood of matching with another compatible passenger. This uncertainty leads to increased congestion along shortest routes and fewer ridesharing trips overall. This paper proposes a route recommendation strategy that goes beyond the shortest route, aiming to address these issues. The proposed strategy results in higher demand, reduced congestion, broader coverage of points of interest (POIs), and an increased probability of finding compatible passengers during a trip. To achieve this, we introduce a time-series forecasting method leveraging a multi-task long short-term memory (LSTM) model to predict demand and traffic patterns in city-zone neighborhoods. These predictions are then used to recommend optimized routes. To evaluate our approach, we tested it on three datasets containing trip and traffic details from New York City (NYC), Los Angeles (LA), and Shenzhen (SZ). Our model demonstrated 96\% accuracy and a 2\% RMSE loss in predicting the expected number of passengers. Furthermore, during route recommendations, we observed a 23\% increase in passenger count for 97\% of trips and a reduction in travel time for the shortest path in 60\% of trips. In light of the above experimentation, we believe that while our approach recommends a longer route than the shortest one (for 40\% cases), it helps taxi drivers to find compatible passengers on most trips which increases the profit of ridesharing services, and reduces the waiting time for passengers.
<br>
<center><img width="700" alt="test" src="https://github.com/user-attachments/assets/598c3ebe-3bd1-44f7-aeae-a31128e64e5a" /></center>

<br>

## Code Description

### 1. Small_Network_Analysis
This code analyze a small network based on New York City, with configurations like using weight or not for route prediction. 
### 2. Data_Prediction_Multi_Task_Learning_V1
This code creates an MTL model that is used to predict parameters. This is the first version of the model that we used.
### 3. Final_Test_Route_Optimization
This code creates the final version of the New York City model in Python and then uses our algorithm to predict the routes. We have provided some tests in the notebook also, but it can be further enhanced. Our algorithm was divided into two functions path_finder and test_and_run.

## Test results

Provided test results of tests also.

## Map results

Provided some open street map results that we got from our EDA

## Dataset

Provided all the important datasets.
