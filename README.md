Linear Regression: Predicting House Prices
This project demonstrates how to build a simple Linear Regression model using a dataset containing house information, with the goal of predicting the house price based on a single feature: the square footage of the living space.

Dataset Overview
The dataset consists of 4600 entries, each representing details of a house. The columns include various features such as:

price: The price of the house (target variable)
sqft_living: The square footage of the living space (used as the feature for prediction)
bedrooms, bathrooms, floors, condition, etc. (other features not used in this model)
Project Objective
The goal of this project is to:

Train a simple Linear Regression model to predict house prices based on the square footage of living space.
Evaluate the performance of the model using appropriate metrics.
Visualize the relationship between square footage and price, along with the regression line.
Requirements
Python 3.x
Libraries:
pandas
numpy
matplotlib
scikit-learn

Files
linear_regression.py: The main Python script that implements the Linear Regression model.
house_data.csv: The dataset file containing house data.
Implementation
Load the dataset: The dataset is loaded from a CSV file into a Pandas DataFrame.
Feature Selection: We use sqft_living as the feature and price as the target variable for Linear Regression.
Train-Test Split: The dataset is split into training and testing sets (80% training, 20% testing).
Model Training: A Linear Regression model is trained using the training set.
Model Evaluation: The model is evaluated using Mean Squared Error (MSE) and R² score.
Visualization: A scatter plot of the actual prices vs. predicted prices is displayed with the regression line.
How to Run
Ensure that the required libraries are installed.
Place the dataset file (house_data.csv) in the project folder.
Run the Python script linear_regression.py:
bash
Copy code
python linear_regression.py
The script will:

Train a Linear Regression model on the data.
Output the performance metrics (Mean Squared Error, R² score).
Display a plot showing the scatter plot of the data points and the fitted regression line.
Model Performance Metrics
After running the script, the following metrics are displayed:

Mean Squared Error (MSE): The average of the squared differences between the actual and predicted house prices.
R² Score: Indicates how well the model explains the variance in the data (ranges from 0 to 1, with 1 being a perfect fit).
Example Visualization
The scatter plot of actual house prices vs. square footage is plotted along with the regression line:

Blue Points: Actual prices of the houses.
Red Line: The predicted regression line based on the model.
Conclusion
This project shows how to build a simple Linear Regression model to predict house prices based on a single feature (sqft_living). The model's performance can be improved by incorporating more features or using advanced regression techniques.

License
This project is licensed under the MIT License.

Acknowledgements
The dataset was taken from a hypothetical real estate listing and can be replaced with any similar dataset for house price prediction.
This project uses Python libraries such as scikit-learn for machine learning and matplotlib for visualization.
