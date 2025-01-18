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

**Dependencies**:

Ensure the following Python libraries are installed:
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
import xgboost
import sklearn
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import accuracy_score, confusion_matrix, classification_report
import matplotlib.pyplot as plt
from sklearn.pipeline import Pipeline
from sklearn.metrics import roc_curve, roc_auc_score, classification_report, accuracy_score, confusion_matrix
from sklearn.ensemble import BaggingClassifier
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import cross_val_score
from sklearn.tree import DecisionTreeRegressor
from sklearn.tree._export import plot_tree

**Warning** : xgboost and sklearn should have the same version
   
!pip install --upgrade xgboost scikit-learn.
   
## Files related to report

The detailed analysis and results are documented in the script itself, particularly through comments and inline explanations.
Check the predictions_with_xgboost.csv file for predicted household consumption levels.
