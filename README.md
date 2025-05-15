# Fuel Consumption Model

This project estimates fuel consumption per trip (liters per 100 km and total fuel 
used) from truck data using regression models. It focuses on segmenting time-series 
data into meaningful trips and analyzing trip-level features that aim to predict 
fuel efficiency.


## Project Steps
1. **Data Preprocessing:** Cleaning and preparing raw time-series data.
2. **Trip Segmentation:** Identifying trip boundaries based on stop patterns.
3. **Feature Engineering:** Extracting meaningful statistics from each trip.
4. **Modeling:** Training regression models to predict fuel consumption.
5. **Evaluation:** Validating and visualizing model performance.

## Contents
- `1_EDA_and_Cleaning.ipynb` — EDA and Data Cleaning  
- `2_Trip_Segmentation.ipynb` — Trip Segmentation & Feature Engineering  
- `3_Model_Training_and_Evaluation.ipynb` — Modeling, Evaluation, and Visualization
