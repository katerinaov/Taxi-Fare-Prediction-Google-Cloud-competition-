# Taxi Fare Prediction Google Cloud competition

This repository contains Taxi Fare Prediction project from Google Cloud competition at Kaggle.

The goal of this project is to predict the fare amount (inclusive of tolls) for a taxi ride in New York City given the pickup and dropoff locations.

The data provided [here](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data)

# Data fields:
key - Unique string identifying each row in both the training and test sets. Comprised of pickup_datetime plus a unique integer, but this doesn't matter, it should just be used as a unique ID field. Required in your submission CSV. Not necessarily needed in the training set, but could be useful to simulate a 'submission file' while doing cross-validation within the training set.


# Features:

pickup_datetime - timestamp value indicating when the taxi ride started.
pickup_longitude - float for longitude coordinate of where the taxi ride started.
pickup_latitude - float for latitude coordinate of where the taxi ride started.
dropoff_longitude - float for longitude coordinate of where the taxi ride ended.
dropoff_latitude - float for latitude coordinate of where the taxi ride ended.
passenger_count - integer indicating the number of passengers in the taxi ride.

# Target:
fare_amount - float dollar amount of the cost of the taxi ride. This value is only in the training set; this is what you are predicting in the test set and it is required in your submission CSV.

Please check the notebook [here] (https://nbviewer.jupyter.org/github/katerinaov/Taxi-Fare-Prediction-Google-Cloud-competition-/blob/master/Taxi%20fare%20predictions.ipynb)
