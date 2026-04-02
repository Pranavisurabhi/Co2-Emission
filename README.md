CO₂ Emission Prediction using Machine Learning
📌 Project Overview

This project focuses on predicting CO₂ emissions of vehicles based on their engine and fuel characteristics using machine learning models.

The problem is treated as a regression task, where the target variable is continuous:

CO₂ Emissions (g/km)
🎯 Objectives
Analyze vehicle data and emission patterns
Perform data preprocessing and feature selection
Train multiple regression models
Evaluate and compare model performance
Identify the best model for prediction
📂 Dataset
Contains vehicle specifications and emission data
Target column: CO₂ Emissions (g/km)
Key Features:
Engine Size
Cylinders
Fuel Consumption (City, Highway, Combined)
Fuel Type
🛠️ Technologies Used
Python 🐍
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
🔍 Exploratory Data Analysis (EDA)
Checked dataset structure using .info(), .describe()
Verified missing values
Visualized data using:
Histograms
Scatter plots
Correlation heatmap

👉 Key Insight:
Fuel consumption shows strong correlation with CO₂ emissions.

🚫 Data Preprocessing
Encoded categorical variables (Fuel Type)
Selected important features based on correlation
Split dataset into training and testing sets (80/20)
📐 Models Implemented
Linear Regression
Decision Tree Regressor
Random Forest Regressor ⭐
Gradient Boosting Regressor
📊 Model Evaluation

Models were evaluated using:

R² Score → Measures explained variance
Mean Absolute Error (MAE) → Average prediction error
Mean Squared Error (MSE) → Penalizes large errors
🏆 Results
Random Forest Regressor achieved the best performance
Accurately captured non-linear relationships in the data
