# British Airways Booking Prediction with Random Forest

## Overview

This project was completed as part of the British Airways Job Simulation on Forage. The goal was to analyze and predict customer booking patterns using historical data and machine learning.

### The notebook includes:
	- Data exploration
	- Feature engineering
	- Model training and evaluation using Random Forest
	- Performance visualization and interpretation


## Dataset

The dataset provided in the simulation includes structured booking data with key variables such as:
- num_passengers: Number of passengers in the booking
- booking_origin: Airport or city where the booking was made
- booking_channel: Platform through which the booking was made
- flight_day: Day of the week of the flight
- booking_day: Day of the week the booking was made
- lead_time: Days between booking and flight
- revenue: Revenue associated with the booking (target variable)
- booking_class: Cabin class booked
- departure_time_band: Grouped time of day for departure
- route: Origin–destination pair



## Approach

### Exploratory Data Analysis (EDA)

Initial data inspection was conducted using .head() and .info(), with further transformation of categorical variables and validation of data types.

### Feature Engineering

Features were encoded where necessary, and lead_time was kept numeric.

### Model

A Random Forest Classifier was selected for its performance and interpretability on tabular data.

#### Model Parameters:
	-	n_estimators=100
	-	random_state=42

#### Evaluation Metrics
	-	Accuracy
	-	Precision, Recall, F1 Score
	-	Confusion Matrix
	-	Feature Importance


## Results Summary
	-	The model performed well on the classification task, particularly for identifying high-revenue bookings.
	-	Important predictive features included lead_time, booking_channel, and route.
	-	Visual outputs (confusion matrix, feature importance) confirmed the model’s decision-making process.

## Environment
	-	Python 3.12
	-	scikit-learn
	-	pandas
	-	matplotlib
	-	seaborn
	-	Jupyter Notebook# British-Airways_ML_Model
