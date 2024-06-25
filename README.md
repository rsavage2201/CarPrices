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
[Project Car Prices RMS (11.1)](https://github.com/rsavage2201/CarPrices/blob/main/Project%20Car%20Prices%20RMS%20(11.1).ipynb)

## Data
The project uses a provided dataset (vehicles.csv).When running the Jupyter notebook a “cleaned” version of the dataset (vehicles_cleaned.csv) will be saved. I did not upload either of these files into the repo as they are too large.

## Data Cleaning 
A full description of the “cleaning” the data underwent is included in the included Project Car Price Report.
In summary, we started with 426,880 rows. We removed those rows with missing key data (price, odometer, year, transmission, manufacturer, title, model and fuel). In addition, missing paint colors were set to ‘unknown’ and text was removed from the 'Cylinders' values, which were then converted to numeric. We were then left with 211,345 to perform our analysis on.

## Key Findings
The key findings of this analysis are included in the included report Project Car Price Report word file. 

In summary, a Random Forrest model was most effective at predicting car price with the following efficacy.
•	Random Forest - Mean Absolute Error (MAE): 3574.082382874411
•	Random Forest - Mean Squared Error (MSE): 35694741.27733562
•	Random Forest - Root Mean Squared Error (RMSE): 5974.507617982893
•	Random Forest - R-squared (R2): 0.7863318381167035

After analyzing the attached data the factor most correlated with the vehicles price is transmission type “other” and the car’s year.  Vehicles with more cylinders are more valuable as are pickups more than trucks and trucks, in turn are more expensive than coupes. Dealers should pay particular attention to cars that are in “Good” condition as this impacts price even more than vehicles that are “like new” or “new”. White is the only color that stands out as having a positive impact on the price.

As for manufacturers, dealers should favor these in the following order
1.	Ram
2.	Ford
3.	Chevrolet
4.	Audi
5.	Jeep

Below is a summar of the major factors impacting price;
- transmission_other	0.39529311
- year	0.381936
- cylinders	0.3323686
- type_pickup	0.25855806
- type_truck	0.179219
- manufacturer_ram	0.164772
- type_other	0.16218604
- condition_good	0.13177163
- paint_color_white	0.11871704
- fuel_other	0.11417593

Conversely, dealers should avoid hatchback vehicles, and Honda as a manufacturer. Higher odometers are correlated with lower prices as are gas vehicles, sedans and vehicles with front wheel drive.
- type_hatchback	-0.1070372
- manufacturer_honda	-0.1283289
- condition_fair	-0.1312539
- odometer	-0.176007
- fuel_gas	-0.1968016
- type_sedan	-0.2330994
- drive_fwd	-0.3087462


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

