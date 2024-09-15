# Smartphone-Prices-A-Regression-Analysis-of-Features-and-Specifications
# Overview

This project aims to predict the prices of smartphones based on their various technical specifications, brand reputation, and additional features using regression analysis techniques. The smartphone industry is highly competitive, with manufacturers constantly introducing new models with diverse features. Accurately predicting smartphone prices can help manufacturers optimize pricing strategies and assist consumers in making informed purchasing decisions. By leveraging data-driven approaches, this project seeks to build and evaluate regression models that can effectively estimate the market price of smartphones based on their attributes.

# Dataset

The dataset used in this project is sourced from Kaggle. It includes a wide range of features that characterize different smartphone models. These features include brand information, hardware specifications, camera details, connectivity options, and more. The key columns in the dataset are:

Brand Information: brand_name, model

Pricing Information: price

Ratings: rating

Hardware Specifications: processor_brand, num_cores, processor_speed, refresh_rate, resolution_width, resolution_height

Camera Details: num_rear_cameras, num_front_cameras, primary_camera_rear, primary_camera_front Connectivity Features: has_5g, has_nfc, has_ir_blaster

Operating System: os

Memory Information: extended_memory_available, extended_upto

The target variable is price, representing the market value of the smartphone.

## Installation

# Install Jupyter Notebook:
Ensure Python is installed on your computer.

# Install Required Packages:
Install the necessary Python packages using your preferred method (e.g., via Anaconda, or directly using pip). The key packages needed for this project include:

numpy

pandas

scikit-learn

matplotlib

seaborn

statsmodels

These packages are essential for data analysis, visualization, and building regression models.

Usage

# Download the Dataset:
Obtain the smartphone dataset from Kaggle.

Run the Analysis: Follow the project steps to explore the data, preprocess it, train regression models, and evaluate their performance.

Review Results: Examine the model's accuracy and other performance metrics to understand how well it predicts smartphone prices.

# Procedure

1.Loading Necessary Libraries.

2.Loading Dataset from a CSV File or from a Table.

3.Summarization of Data to Understand Dataset (Descriptive Statistics).

4.Visualization of Data to Understand Dataset (Plots, Graphs, etc.).

5.Data Pre-processing Imbalanced Learn Techniques, Data Transformation, Cross Validation.

6.Hyper parameter Tuning to Find the Optimal Parameters for the Regression Models.

7.Applying Different Learning Algorithms on the Training Dataset.

8.Applying the Standard Scaler and re-performing the same procedure.

# License

This project is licensed under the Kaggle Dataset License as provided by the dataset's creator.

# Results

The trained regression models achieved high accuracy in predicting smartphone prices based on the features provided in the dataset. The models demonstrated strong correlations between technical specifications, brand value, and pricing. Among the models tested, we got the best accuracies with 85% for Random Forest Regressor and Bagging Regressor, indicating that these models can effectively estimate smartphone prices with high precision.
