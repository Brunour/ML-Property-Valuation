# Real Estate Price Prediction

## 📌 Project Overview

This project explores the relationship between the selling prices of properties and the socioeconomic and infrastructure characteristics of different neighborhoods in Buenos Aires. The goal is to determine if sellers are pricing properties fairly based on location and surrounding conditions, and to identify the most influential factors in property pricing.

The project was developed as a practice exercise inspired by a course in Python for Data Science, but it can be expanded to use real data from governmental sources in larger-scale applications.

## 🛠️ Technologies Used

- Python: Programming language for all data manipulation and model building.
- Google Colab: Development environment for running Python code.
- Pandas: For data manipulation and cleaning.
- NumPy: To handle numerical operations.
- Matplotlib & Seaborn: For data visualization and plotting.
- Scikit-learn: To implement the Linear Regression model.
- Google Drive: To store and access datasets.

## 🗂️ Data

Neighborhood Data: Extracted from the Government of Buenos Aires' website, providing socioeconomic and infrastructure information.
Property Listings: Simulated data for the properties, with location codes created specifically for this project. The data could easily be replaced with real location codes in future iterations.
The dataset includes:

Neighborhood codes
Property characteristics (e.g., size, type)
Socioeconomic factors (e.g., security, schools, infrastructure)

## 🎯 Project Objectives

Predict Fair Pricing: Analyze whether property sellers are pricing properties fairly, given the neighborhood and surrounding conditions.
Identify Key Features: Determine which factors (e.g., security, infrastructure, etc.) have the greatest impact on the price of properties.
This project aims to help potential buyers and sellers better understand the influence of neighborhood factors on property prices.

## 📊 Visualizations

Bar Charts: To compare property prices across different neighborhoods.
Distribution Plots: To analyze the distribution of prices.
Heatmaps: To visualize the correlation between property prices and various neighborhood features (e.g., safety, infrastructure, schools).

## 🔍 Model & Methodology

The project employs a Linear Regression model to predict property prices based on neighborhood characteristics.

Key Steps:
Data Cleaning & Preparation: Using Pandas, I cleaned and transformed the dataset for analysis.
Model Training: Implemented a Linear Regression model using Scikit-learn.
Feature Selection: Analyzed the importance of neighborhood features to see which had the most significant impact on pricing.
Model Evaluation: Evaluated the model performance using common metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) (Explanation of these metrics below).

## 📈 Model Performance

Evaluation Metrics:
Mean Absolute Error (MAE): Measures how far off the predictions are, on average. Lower is better.
Root Mean Squared Error (RMSE): Gives a sense of how much error the model makes in its predictions. A lower RMSE means better accuracy.
These metrics help determine how well the model is predicting prices compared to actual prices.

## 👥 Target Audience

This project is designed for:

People interested in Data Science and Machine Learning.
Those looking to understand how socioeconomic factors influence real estate prices.
Recruiters who want to assess my skills in data analysis, Python programming, and machine learning.
Learners who are just starting in Data Science and want to see a practical, beginner-friendly project.

## 🔧 Potential Improvements

Replace simulated data with real property listings and neighborhood codes from Buenos Aires.
Use more advanced models (e.g., Random Forests, Gradient Boosting) to improve prediction accuracy.
Incorporate more features, such as historical price trends and inflation data.

## 📚 Conclusion

This project not only demonstrates the process of data cleaning, visualization, and predictive modeling using Python and Machine Learning, but also serves as a practical tool for understanding the relationship between property pricing and neighborhood characteristics. Future iterations could make this tool valuable for buyers, sellers, and real estate agents alike.
