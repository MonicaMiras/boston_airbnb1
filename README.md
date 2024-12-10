# Airbnb Price Prediction using Random Forest Regression

Project Overview

This project aims to predict the price of Airbnb listings based on various features such as accommodation capacity, number of bathrooms, number of bedrooms, and seasonal trends. The model uses a Random Forest Regressor to make predictions on the prices of Airbnb listings in a given dataset.

Objective

The goal of this project is to build a machine learning model that can accurately predict the price of Airbnb listings based on available features. This model is intended to help users estimate prices based on different factors such as location, accommodation type, and seasonal demand.

Data Description

The dataset used for this project consists of two main tables:
	•	Listings: Contains information about individual Airbnb listings, including the price, number of rooms, and other attributes.
	•	Calendar: Contains information about the availability of the listings, including the dates when a listing is available or not.

For the purposes of this project, the relevant features for predicting the price include:
	•	price: The target variable (price of the listing).
	•	accommodates: The number of people the listing can accommodate.
	•	bathrooms: The number of bathrooms in the listing.
	•	bedrooms: The number of bedrooms.
	•	beds: The number of beds in the listing.
	•	season: The season (Spring, Summer, Fall, Winter) during which the listing is available.

Approach
	1.	Data Cleaning:
	•	Merged the listings and calendar tables into a single dataset for analysis.
	•	Handled missing values and ensured that the relevant features were available for modeling.
	2.	Feature Engineering:
	•	Created dummy variables for categorical features like season.
	3.	Modeling:
	•	Used the Random Forest Regressor algorithm to build the regression model.
	•	Split the data into training and testing sets (80% training, 20% testing).
	•	Trained the model to predict the price of the listing based on the features provided.
	4.	Model Evaluation:
	•	Evaluated the model using Mean Squared Error (MSE), which is a common metric for regression problems. A lower MSE indicates better model performance.

Libraries Used
	•	pandas: For data manipulation and cleaning.
	•	sklearn: For building and evaluating the machine learning model.
	•	numpy: For numerical operations.
	•	matplotlib and seaborn: For data visualization.

Evaluation Metrics
	•	Mean Squared Error (MSE): This is the metric used to evaluate the performance of the model. A lower MSE indicates that the model is making better predictions.

Future Work
	1.	Model Tuning: Explore hyperparameter tuning (e.g., number of estimators, max depth) to improve model performance.
	2.	Additional Features: Incorporate other features such as location (latitude and longitude) and review ratings to improve the model’s accuracy.
	3.	Model Comparison: Compare the Random Forest model with other regression models such as Gradient Boosting or Linear Regression to see which yields better results.

Conclusion

This project demonstrates how to use machine learning to predict the price of Airbnb listings based on various factors. By training a Random Forest Regressor model, we were able to create a model that provides a reasonable estimate of the price based on the features provided.
