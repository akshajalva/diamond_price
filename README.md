# Cubic Zirconia Price Prediction Using Regression #

This project focuses on predicting the price of cubic zirconia stones based on various physical and geometric features. The dataset includes attributes such as carat, depth percentage, table percentage, and price, among others. The goal is to build a machine learning model that accurately predicts the price of cubic zirconia stones and provides insights into the relationships between these features.

Dataset Features
The dataset includes the following features for each cubic zirconia stone:
Carat: Weight of the cubic zirconia
Cut: Quality of the cut (Fair, Good, Very Good, Premium, Ideal)
Color: Color grading from D (best) to J (worst)
Clarity: Clarity grade from FL (Flawless) to I3 (most inclusions)
Depth: Height as a percentage of average diameter
Table: Width of the table as a percentage of average diameter
X: Length in millimeters
Y: Width in millimeters
Z: Height in millimeters
Price: Price in US dollars (target variable)

Machine Learning Models
We employ several regression models to predict the price:
Linear Regression
Decision Trees
Random Forests
XGBoost

Project Workflow
Data Preprocessing: Handling missing values, encoding categorical variables, and scaling numerical features.
Exploratory Data Analysis (EDA): Visualizing relationships between features and identifying patterns.
Feature Engineering: Creating new features or transforming existing ones to improve model performance.
Model Training and Evaluation: Training multiple models and comparing their performance using metrics like RMSE, and R² score.

After training and testing the 4 models mentioned above the performance of the XGBoost is better than the rest with a r2 score of 0.9802
