# **Car Price Prediction Project**

**Objective:**

The primary goal of this project was to develop a model that can accurately predict car prices based on various features.

**Dataset:**

The dataset, sourced from Kaggle, comprises various features of different car models, including technical specifications and categorical attributes.

link to dataset : https://www.kaggle.com/datasets/hellbuoy/car-price-prediction?select=CarPrice_Assignment.csv

**Overview of the Process :**

1. Data Collection:

 * The dataset was imported, containing various features related to car specifications and prices.

2. Data Analysis and Preprocessing:

 * Exploratory Data Analysis (EDA): Initial examination of the dataset to understand its structure and summarize its main characteristics.
 * Handling Missing Values: Checked for any missing values and ensured the dataset was clean.
 * Feature Encoding: Categorical variables were encoded using Label Encoding to convert them into numerical values.
 * Data Standardization: Numerical features were standardized to ensure they have a mean of 0 and a standard deviation of 1, which helps in improving the performance of machine learning algorithms.

3. Correlation Analysis:

 * A correlation matrix was generated to understand the relationships between different features and identify any multicollinearity.

4. Feature Selection:

5. Model Selection and Evaluation:

 * Three different models were evaluated using cross-validation to determine their performance in predicting car prices

6. Model Training:

 * The dataset was split into training and testing sets. The XGBoost Regressor model was trained on the training data.

7. Model Evaluation:

 * The model's performance was evaluated on both the training and testing data.
 * Visualization of the actual vs. predicted prices was done .
8. Predictive System:

 * A predictive system was developed to allow users to input car specifications and predict the price using the trained XGBoost model.
