# Airbnb Price Prediction

This project analyzes Airbnb listings to predict the price of properties based on various features, such as room type, location, amenities, and review scores. The goal of this analysis is to understand the factors that influence the pricing of Airbnb properties and to build a predictive model.

## Project Overview

Airbnb has become a popular platform for booking unique stays around the world. Understanding how different features of a listing impact the price can help hosts price their properties more effectively. In this project, we explore the Airbnb listing data, clean it, build a linear regression model, and evaluate its performance.

## Data Description

The dataset includes the following features:

Price: The price of the listing (target variable).
Room Type: Type of room (e.g., Entire Home, Private Room).
Property Type: Type of property (e.g., House, Apartment, etc.).
Accommodates: Number of people the listing can accommodate.
Review Scores: Ratings for cleanliness, accuracy, location, value, etc.
Other Features: Bedrooms, bathrooms, beds, and minimum/maximum night restrictions.


# Analysis and Approach

## Data Preprocessing:

Cleaned the dataset by handling missing values and removing outliers.
Converted categorical variables (e.g., room_type, property_type) into numeric values using one-hot encoding.
Exploratory Data Analysis (EDA):
Explored the relationship between features and price using visualizations.
Identified key features that correlate with the price.
Modeling:
Built a linear regression model to predict price based on the features.
Evaluated the model's performance using various metrics, including Root Mean Squared Error (RMSE) and R² score.


## Model Performance

The linear regression model was trained to predict the price based on a set of selected features. The model was evaluated using the following metrics:

R² Score: 0.21
The R² score indicates that the model explains about 21% of the variance in the price. This suggests that other factors not captured by the model contribute to the price variability.
RMSE: 93
The Root Mean Squared Error (RMSE) is 93, meaning that the predicted price is, on average, off by 93 units (e.g., dollars). This value reflects the model’s predictive accuracy, and a lower RMSE would indicate better prediction performance.
