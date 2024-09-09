# Zomato-project


### Introduction
Prepare the Zomato dataset for analysis and modeling by handling missing values, encoding categorical variables, and scaling numerical features to predict customer ratings effectively.




#### 1.1. Problem Statement

Predicting customer ratings based on features like price, location, and cuisine. Emphasize the importance of accurate rating predictions for improving restaurant performance and customer satisfaction.
#### 1.2 Objective

To build a predictive model that estimates Zomato customer ratings accurately using the available features.
#### 1.3 Data Collection

The dataset used for this project is collected from Google. It includes various features relevant to predicting customer ratings on Zomato.


#### 1.4 Data Description

Describe the dataset, focusing on key features such as:
Price: Pricing levels of the restaurants.
Location: Geographic location or neighborhood.
Cuisine: Types of cuisine offered.
Ratings: Customer ratings of the restaurants.

#### 1.5 Exploratory Data Analysis (EDA)

Perform EDA to identify trends, distributions, and relationships among features. Analyze how various factors influence customer ratings and uncover any patterns or anomalies.
#### 1.6 Data Preprocessing

Address data quality issues:
Handle missing values, especially in the 'cuisine' column.
Detect and treat outliers.
Apply categorical encoding for non-numeric features.
Scale numerical features as necessary.

#### 1.7 Visualization

Use visual tools such as histograms, boxplots, and scatter plots to further explore and understand the data. Visualizations will help reveal insights and guide feature engineering.

#### 1.8 Feature Engineering

Feature engineering involves transforming data to improve model performance. Label encoding converts categorical features into numerical values using LabelEncoder, while feature scaling standardizes or normalizes numerical features to ensure equal contribution. Standardization centers data around zero with unit variance, while normalization scales data between 0 and 1. Tools like StandardScaler and MinMaxScaler facilitate these transformations. 

#### 1.9 Data Splitting

Split the dataset into training and testing sets. This is crucial for validating the model's performance and ensuring it generalizes well to unseen data.

#### 2.0 Model Selection

Choose appropriate machine learning models for predicting customer ratings. Consider models like Linear Regression, Decision Trees, Random Forest, and Gradient Boosting.

#### 2.1 Model Training & Evaluation

Train the selected models and evaluate their performance using metrics such as R², RMSE, and MAE. Compare the models to determine which provides the best predictions.

#### 2.2Feature Selection

Identify and select the most relevant features that contribute to the prediction of ratings. Feature selection improves model performance and reduces complexity.

#### 2.3 Hyperparameter Tuning

Optimize the models’ hyperparameters to enhance their predictive accuracy. Use techniques like grid search or random search to find the best parameter values.
#### 2.4 Save the Model

Save the trained GradientBoostingRegressor model for future use. This allows you to make predictions on new data without retraining the model.

#### 2.5 Conclusion

Summarize the findings, highlighting that the GradientBoostingRegressor has shown superior performance with the lowest RMSE, MSE, and MAE, and the highest R² score. Discuss how this model effectively captures data patterns.

