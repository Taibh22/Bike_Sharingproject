# Bike Dataset 

This repository contains data exploration, data cleaning, feature engineering, and machine learning models on a bike dataset. The dataset contains information about bike rentals in Washington, D.C. The goal of this project is to predict the count of bike rentals based on various features.

## Getting started

To get started with this project, you will need to have Python 3 installed on your system, along with the following libraries: pandas, matplotlib, seaborn, numpy, scikit-learn, and statsmodels.

You can clone this repository using the following command:

bash
git clone [https://github.com/Taibh22/Bike_Sharingproject.git
](https://github.com/Taibh22/Bike_Sharingproject.git)

## Data Description

The dataset contains the following columns:

- instant: A unique sequential ID number for each row
- dteday: The date on which the data was recorded
- season: The season of the year (1 = winter, 2 = spring, 3 = summer, 4 = fall)
- yr: The year (0 = 2011, 1 = 2012)
- mnth: The month of the year (1 to 12)
- holiday: Whether or not the day was a holiday
- weekday: The day of the week (0 to 6)
- workingday: Whether or not the day was a working day
- weathersit: The weather situation (1 = clear, 2 = mist, 3 = light snow/rain, 4 = heavy snow/rain)
- temp: The temperature in Celsius
- atemp: The "feels like" temperature in Celsius
- hum: The humidity level
- windspeed: The wind speed
- casual: The number of casual (non-registered) bike rentals
- registered: The number of registered bike rentals
- cnt: The total number of bike rentals (casual + registered)

## Exploratory Data Analysis (EDA) and Data Wrangling

The first step is to explore the dataset and handle any missing values. We will use pandas and matplotlib libraries to explore and visualize the dataset. We will also use seaborn to plot correlation matrices and other visualizations. 

We will also check for any outliers in the dataset and remove them if necessary. We will also check for any duplicate rows and remove them if necessary.

## Handling Missing Values

We will handle any missing values in the dataset by either removing the rows with missing values or filling them with appropriate values. We will use various techniques to fill the missing values such as mean, median, or mode.

## Feature Engineering Techniques

We will engineer new features from the existing features in the dataset. We will use techniques such as binning, one-hot encoding, and scaling to create new features that can improve the performance of our machine learning models.

## Evaluation Matrices

We will use various evaluation matrices such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) to evaluate the performance of our machine learning models.

## Machine Learning Models

We will train various machine learning models on the dataset. We will use scikit-learn and statsmodels libraries to train the following models:

- Linear Regression
- Decision Trees
- Random Forest
- XGBoost
- Polynomial Features 
- Regularization

We will also optimize the hyperparameters of each model using techniques such as Grid Search and Random Search.

## Conclusion

In conclusion, this project provides an end-to-end solution for handling a real-world dataset and training machine learning models on it. The techniques used in this project can be applied to other datasets as well.
