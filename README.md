# Udacity-DeepLearningND-P1-BikeSharing
Predict daily bike rental ridership. Build and train a neural network from scratch to predict the number of bike-share users on a given day

## Probem Description
- Regression: 
  Prediction of bike rental count hourly or daily based on the environmental and seasonal settings.
	
- Event and Anomaly Detection:  
	Count of rented bikes are also correlated to some events in the town which easily are traceable via search engines.
	For instance, query like "2012-10-30 washington d.c." in Google returns related results to Hurricane Sandy. Some of the important events are 
	identified in [1]. Therefore the data can be used for validation of anomaly or event detection algorithms as well.


## Dataset 
From Udacity - "Bike-sharing rental process is highly correlated to the environmental and seasonal settings. For instance, weather conditions,
precipitation, day of week, season, hour of the day, etc. can affect the rental behaviors. The core data set is related to  
the two-year historical log corresponding to years 2011 and 2012 from Capital Bikeshare system, Washington D.C., USA which is 
publicly available in http://capitalbikeshare.com/system-data. We aggregated the data on two hourly and daily basis and then 
extracted and added the corresponding weather and seasonal information. Weather information are extracted from http://www.freemeteo.com. "


## Getting Started - Requirements
Python packages 
- python 3.6
- numpy 
- pandas 
- matplotlib
