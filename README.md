# 📊 Real Estate Analysis

## 📝 Overview

The objective of this project was to analyze a dataset containing housing price details linked with various attributes such as distance from the city center, property count, number of rooms, etc. The goal was to identify key factors affecting housing prices in Melbourne suburbs and provide insights into the real reasons behind fluctuations in real estate prices.

## 🛠️ Tools and Steps

**Tools:** 🐍 Python, 📊 Pandas, 📈 Matplotlib, 📊 Seaborn, 📓 Jupyter Notebook, 📊 Excel.

**Steps:**
- 🧹 Data Cleaning and Preprocessing
- 📊 Exploratory Data Analysis (EDA)
- 📈 Visualization
- 📊 Feature Engineering
- 📈 Model Building
- 📊 Hyperparameter Tuning
- 📝 Insights and Recommendations

## 🧹 Data Preparation and Cleaning

The dataset was acquired from Kaggle and underwent cleaning and preprocessing to handle missing values, remove duplicates, and prepare it for analysis. Columns like CouncilArea, Suburb, Address, SellerG, Postcode, and Date were dropped due to high correlation or lack of relevance.

## 📊 Exploratory Data Analysis

### 📈 Descriptive Statistics

After null value treatment, the dataset contained 48,433 rows with 8 categorical and 5 numerical features. The minimum, maximum, average, and standard deviation of numerical variables were calculated.

### 📊 Visualizations

Scatterplots were used to visualize similarities between variables like number of rooms, price, postcode, property count, and distance. Histograms were also used to show the distribution of these variables.

## 📈 Model Building and Hyperparameter Tuning

### 📈 Baseline Method

A simple baseline method was used where the median value from the training data was predicted for all test instances.

### 📈 Models Tested
- Linear Regression
- Decision Trees
- Random Forest Regressor

### 📊 Hyperparameter Tuning with GridSearchCV

GridSearchCV was employed to find the optimal hyperparameters for the Random Forest Regressor.

## 📊 Feature Importances

All features were considered in the final model to ensure comprehensive analysis.

## 📝 Recommendations

Based on the analysis, the following recommendations are proposed:
- 🎯 Focus on attributes like distance from city center and property count for pricing strategies.
- 📈 Consider the number of rooms as a significant factor affecting housing demand.
- 💡 Explore additional datasets to include more features like amenities, age of property, etc.

## 📝 Conclusion

The analysis provided valuable insights into the key factors affecting housing prices in Melbourne suburbs. The Random Forest model emerged as the best fit for predicting housing prices based on the available features.
