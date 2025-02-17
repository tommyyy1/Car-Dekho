# Car-Dekho
Project Overview

This project aims to predict the price of used cars based on various features using historical data from CarDekho. The model utilizes advanced machine learning techniques, including feature engineering, regularization, and hyperparameter tuning. Additionally, a Streamlit web application is developed to allow users to input car details and receive price predictions in real-time.

Table of Contents
Data Processing
Exploratory Data Analysis (EDA)
Model Development
Model Evaluation
Optimization
Deployment
Results
Project Evaluation Metrics
Installation & Usage
Contributing

Data Processing
Import and Concatenation:
Load and merge datasets from different cities into a structured format.
Add a 'City' column to indicate the city of the data.

Handling Missing Values:
Use mean/median for numerical values and mode for categorical values.

Standardizing Data Formats:
Convert string-based numerical data (e.g., "70 kms") to integers.
Encoding Categorical Variables:
Apply one-hot encoding and label encoding where necessary.
Normalizing Numerical Features:Used Standard Scaling.

Removing Outliers:
Removed mixed data types which resulted in removing many columns and most of the columns are repeatative. 
Filtered values before applying IQR analysis.
Exploratory Data Analysis (EDA)

Descriptive Statistics:
Compute mean, median, mode, and standard deviation.

Data Visualization:
Generate scatter plots, histograms, box plots, and correlation heatmaps.

Feature Selection:
Use correlation analysis and feature importance techniques using extra tree regressor.

Model Development
Train-Test Split:
Split the dataset into training and testing sets (e.g., 80-20 ratio).

Model Selection:
Train multiple models, including Linear Regression, Decision Trees, Random Forests, and Gradient Boosting.

Model Training:
Use cross-validation for robust performance.

Hyperparameter Tuning:
Optimize parameters using Grid Search or Random Search.

Model Evaluation
Performance Metrics:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R-squared
Model Comparison:
Evaluate models based on the above metrics.

Optimization
Feature Engineering:
Create interaction terms and other meaningful features.
Regularization:
Apply Lasso (L1) and Ridge (L2) to prevent overfitting.

Deployment
Streamlit Web App:
Users can input car details and get predictions.

User Interface:
Designed for an intuitive experience with error handling.

Results
A functional and accurate machine learning model.
Comprehensive dataset analysis and visualizations.
An interactive Streamlit web application for real-time price predictions.


Installation & Usage

Clone the repository:
git clone https://github.com/yourusername/CarDheko-PricePrediction.git
cd CarDheko-PricePrediction

Install dependencies:
pip install -r requirements.txt

Run the Streamlit app:
streamlit run app.py
