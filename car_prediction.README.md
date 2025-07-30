🔍 Project Description: Car Price Prediction Using Machine Learning
In this project, I utilized a car price dataset sourced from Kaggle to build an end-to-end regression model for predicting vehicle selling prices. The workflow involved thorough data cleaning, visualization, feature engineering, and machine learning model training.
🧹 Data Preprocessing & Feature Engineering
Performed label encoding to convert categorical features such as Fuel Type, Transmission, and Selling Type into numerical format, enabling compatibility with ML algorithms.
Conducted EDA (Exploratory Data Analysis):
Checked for and handled null values and duplicate records.
Used correlation heatmaps and matrices to identify relationships between features and their impact on the target variable, Selling Price.
Dropped low-impact features such as Owner and Kms_Driven after analyzing their minimal contribution via correlation analysis.
📊 Data Visualization
Utilized Seaborn and Matplotlib for graphical representation:
Bar plots showing average selling price by car name.
Identified and visualized budget-friendly cars (Selling Price ≤ 5 lakhs).
Average price by fuel type and comparison of present price vs selling price using scatter plots to assess variations.
🤖 Model Training
Split the dataset into training and testing sets.
Applied the Random Forest Regressor, a powerful ensemble learning method that builds multiple decision trees and aggregates their results for improved accuracy and reduced overfitting.
📈 Model Performance
The model achieved strong predictive performance:
R² Score: 0.9629 — indicating a high level of explained variance.
MAE (Mean Absolute Error): 0.48 — showing low average prediction error.
RMSE (Root Mean Squared Error): 0.82 — indicating minimal deviation from actual values.
📃 Final Output
The final output presents:

Actual Price, Predicted Price, and Prediction Error (difference between the two),
allowing clear comparison and error tracking for each instance.

