# gold-price-prediction

Gold Price Prediction using ML. 
Data Set : https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data

This repository contains my solution to the Kaggle challenge Gold Price Problem, which aims to predict the gold price for the next 30 days based on historical data.

Data
The data consists of daily gold prices from January 1, 1968 to August 11, 2021, obtained from here. The data has two columns: Date and Price (USD).

Method
I used a simple linear regression model to fit the data and make predictions. I split the data into training (80%) and testing (20%) sets, and used the mean absolute error (MAE) as the evaluation metric. I also plotted the actual and predicted values on a line chart to visualize the results.

Results
The linear regression model achieved a MAE of 23.76 on the testing set, which means that the average error of the predictions is about $24. The plot shows that the model captures the overall trend of the gold price, but fails to capture the fluctuations and seasonality.
