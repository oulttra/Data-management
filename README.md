# Data-management

# USA Household Electricity Consumption Prediction Project

This project focuses on predicting whether a household’s electricity consumption cost in the USA will be high or low (year 2020) using various machine learning techniques. The analysis incorporates data cleaning, and multiple classification models.

## Project Structure

- **Data retrieval**:
  - Combines three datasets (`database1.csv`, `database2.csv`, `database3.csv`) using unique identifiers.
  - Handles missing values and removes duplicates.
  - Identifies and removes outliers for robust analysis.

- **Exploratory Data Analysis**:
  - Analyzes missing values, outliers, and distributions.
  - Visualizes key variables like HDD65 (heating degree days), CDD65 (cooling degree days) and others variables.

- **Machine Learning Models**:
  - Logistic Regression
  - Bagging Classifier
  - XGBoost Classifier

## Instructions to Build and Run the Project

1. **Dependencies**:
   Ensure the following Python libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
