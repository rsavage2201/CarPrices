# Project CarPrices
Practical Assignment 11.1 What drives the price of a car?

## Table of Contents 
- Description
- Jupyter Notebook 
- Data
- Results 
- Visualizations
- Contact Information

## Description
This project analyzes a dataset on used car prices and provides a clear recommendation the client -- a used car dealership -- as to what consumers value in a used car.

## Jupyter Notebook
Run the below Jupyter notebook to see the analysis

## Data
The project uses a provided dataset (vehicles.csv). I have also included a “cleaned” version of the dataset (vehicles_cleaned.csv) in this repo.  Ensure the data file is placed in the data directory.

## Data Cleaning 
A full description of the “cleaning” the data underwent is included in the included Project Car Price Report.
 In summary, we started with 426,880 rows. We removed those rows with missing key data (price, odometer, year, transmission, manufacturer, title, model and fuel). In addition, missing paint colors were set to ‘unknown’ and text was removed from the 'Cylinders' values, which were then converted to numeric. We were then left with 211,345 to perform our analysis on.

## Key Findings
The key findings of this analysis are included in the included report Project Car Price Report. 
In summary, a Random Forrest model was most effective at predicting car price. Factors that deals should seek out are year, transmission type, cars with more cylinders, pickups and trucks. Cars that are in “good” condition and are white should also be favored.
Dealers should avoid, Toyotas, gas vehicles with forward drives, high odometers and sedans. 

## Visualizations
The following visualizations are also included
-	svd_plot.png
-	kmeans_plot.png
-	pca_plot.png
-	simple_linear_regression_plot.png
-	multiple_linear_regression_plot.png
-	actual_vs_predicted_prices_ridge.png
-	actual_vs_predicted_prices_lasso.png
-	actual_vs_predicted_prices_rf.png
-	actual_vs_predicted_prices_svr.png
-	actual_vs_predicted_prices_gbr.png

## Contact Information
You can contact me on (rowland_savage@yahoo.com)

