# Bike_Sharing_Demand_Prediction
This project aims to enhance the mobility and convenience of the public through bike-sharing programs in metropolitan areas. One of the main challenges is maintaining a consistent supply of bikes for rental.

Bike-sharing systems are automated and enable people to rent and return bikes at various locations. The project focuses on utilizing historical data on factors such as temperature and time to predict the demand for the bike-sharing program in Seoul.

There were approximately 8760 records and 14 attributes in the dataset.

We started by importing the dataset, and necessary libraries and conducted exploratory data analysis (EDA).

Outliers and null values were removed from the raw data and treated. Data were transformed to ensure that it was compatible with machine learning models.

We handled target class imbalance using square root normalization.

Then finally cleaned and scaled data was sent to 11 various models, the metrics were made to evaluate the model, and we tuned the hyperparameters to make sure the right parameters were being passed to the model.

When developing a machine learning model, it is generally recommended to track multiple metrics because each one highlights distinct aspects of model performance. We are, focusing more on the R2 score and RMSE score.

The R2 score is scale-independent, which means that it can be used to compare models that are fit to different target variables or to target variables that have different units of measurement. This is particularly useful when comparing models for different problems, as it allows for a direct comparison of the performance of the models, regardless of the scale of the target variable

Index

Problem Statement

Know Your Data

Understanding Your Variables

EDA

Data Cleaning

Feature Engineering

Model Building

Model Implementaion.

Conclusion
