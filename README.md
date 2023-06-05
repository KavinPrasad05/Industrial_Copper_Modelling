# Industrial_Copper_Modelling

Application Link: https://kavinprasad05-industrial-copper-modelling-stream-78lfqx.streamlit.app/

## Project Overview

This project aims to develop two machine learning models for the copper industry to address the challenges of predicting selling price and lead classification. The manual prediction of these factors can be time-consuming and may not result in optimal pricing decisions or accurately capture leads. Therefore, the models will utilize advanced techniques such as data normalization, outlier detection and handling, handling data in the wrong format, identifying the distribution of features, and leveraging tree-based models, specifically the decision tree algorithm, to predict the selling price and leads accurately.

## Regression Model Details

The copper industry deals with less complex data related to sales and pricing. However, this data may suffer from issues such as skewness and noisy data, which can affect the accuracy of manual predictions. To address these challenges, a machine learning regression model will be developed.

The regression model will perform the following steps:

1. Explore skewness and outliers in the dataset.
2. Transform the data into a suitable format and perform any necessary cleaning and pre-processing steps.
3. Develop a machine learning regression model that predicts the continuous variable 'Selling_Price' using the decision tree regressor.

## Classification Model Details

Another area where the copper industry faces challenges is in capturing leads. A lead classification model is a system for evaluating and classifying leads based on how likely they are to become a customer. In this project, a machine learning classification model will be developed to address this challenge.

The classification model will perform the following steps:

1. Use the STATUS variable with WON considered as Success and LOST considered as Failure. Remove data points with statuses other than WON or LOST.
2. Transform the data into a suitable format and perform any necessary cleaning and pre-processing steps.
3. Develop a machine learning classification model that predicts the status (WON or LOST) using the decision tree classifier.

## Solution

The solution will involve the following steps:

1. Explore skewness and outliers in the dataset to understand the data distribution.
2. Transform the data into a suitable format, handle missing or incorrect values, and perform data cleaning and pre-processing steps.
3. Develop a regression model using the decision tree regressor to predict the selling price.
4. Develop a classification model using the decision tree classifier to predict the lead status (WON or LOST).
5. Create a Streamlit web application where users can input values for each column and get the predicted selling price or lead status.

## Requirements

This project requires the following libraries to be installed:

- NumPy
- Pandas
- Scikit-learn
- Streamlit

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required libraries listed above.
3. Run the Streamlit app using the command: `streamlit run app.py`.
4. Enter the values for each column in the web application to get the predicted selling price or lead status (WON or LOST).

