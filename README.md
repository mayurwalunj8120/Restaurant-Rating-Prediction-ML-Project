Restaurant Rating Prediction using Machine Learning

This project develops a complete end-to-end Machine Learning pipeline to predict restaurant ratings using various real-world features such as customer votes, cuisine type, price, city, and delivery options.
It demonstrates the full Data Science workflow — data cleaning, preprocessing, EDA, feature engineering, model building, evaluation, and prediction.

🔍 Project Overview
🎯 Objective

To build a regression model that can accurately predict the overall restaurant rating using multiple restaurant-level features.

🎯 Target Variable

Rating (continuous numeric value)

🧹 Data Preprocessing
✔ Steps Completed

Removed duplicate and inconsistent records

Handled missing values

Cleaned text fields for Cuisine, City, Place Name

Encoded categorical variables

Scaled numerical features

Identified correlations and important predictors

Visualized feature relationships using charts

🔑 Features Used

Dining Votes

Delivery Votes

Total Votes

Price

Cuisine

Place Name

City

Best Seller

Online Delivery

📊 Exploratory Data Analysis

Key insights obtained through visualizations and statistical summaries:

Higher dining votes strongly correlate with higher ratings

Popular cuisines show consistent rating patterns

Some cities have better overall restaurant ratings

Best seller restaurants generally receive higher ratings

Votes and pricing influence ratings non-linearly

🤖 Machine Learning Models

The following models were built and compared:

Model	Notes
Linear Regression	Good baseline model
Random Forest	Strong performance with non-linear patterns
XGBoost	⭐ Best overall accuracy and generalization
Metrics Used

MAE

MSE

RMSE

R² Score

This makes the model reusable and deployment-ready.

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-learn

Random Forest, XGBoost

Matplotlib, Seaborn

Jupyter Notebook

📝 Key Insights

Dining and delivery votes are strong predictors of rating

Cuisines and city/location heavily influence user preferences

Best seller items boost restaurant ratings

Customer engagement (votes) correlates with higher average ratings
