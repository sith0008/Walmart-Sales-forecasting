# M5 Forecasting Walmart Sales Prediction 

This is a sales forecasting project for the M5 Forecasting challenge on Kaggle. The task is to perform time series predictions for two 28-day time periods for 30490 products as well as 12350 aggregated time series. More information about the dataset can be found at https://www.kaggle.com/c/m5-forecasting-accuracy

## M5_Forecasting_preprocess

This notebook serves to transform the dataset into a more analysis and model-friendly format. It also reduces the memory of the data files to account for RAM limitation.

## M5_Forecasting_EDA

This is an exploratory data analysis notebook that looks into the trends in the datasets. 
- Aggregated sales trend against different units of time
- How product prices change over time
- Relationships between day-of-week and sales
- Relationships between holidays and sales

## M5_Forecasting_modelling

This set of notebooks contains the code for three remaining phases of the project: feature engineering, model training and prediction. This project treats the time series prediction as a supervised learning problem, using 1) Lightgbm, a gradient boosting framework, and 2) a simple Deep Neural network to make the predictions.
