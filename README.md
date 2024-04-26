# Breast Cancer Detection

## Overview
This Jupyter Notebook file contains code for detecting breast cancer using machine learning algorithms. The dataset used in this project is `data.csv`.

## Data Preprocessing

### Import Libraries and Dataset
- Necessary libraries like NumPy, Matplotlib, Pandas, Seaborn, and scikit-learn are imported.
- The dataset is imported using Pandas' `read_csv` function.

### Data Exploration
- The shape and information of the dataset are examined.
- Categorical and numerical columns are identified.
- Statistical summary of the dataset is generated.

### Dealing with Missing Values
- Missing values are checked and dropped from the dataset.

### Dealing with Categorical Data
- Categorical columns are identified and converted into dummy variables.
- Boolean values are replaced with 0s and 1s.

## Data Visualization
- Countplot is used to visualize the distribution of classes (Benign and Malignant).
- Correlation matrix and heatmap are plotted to explore relationships between variables.

## Model Building
Two models are built:
1. Logistic Regression
2. Random Forest Classifier

### Logistic Regression
- The model is trained and evaluated.
- Cross-validation is performed to assess model performance.
- Randomized search is conducted to find the best parameters.
- Final model with optimized parameters is trained and evaluated.
- Prediction function is defined to predict the class of new data.

### Random Forest Classifier
- The model is trained and evaluated.
- Cross-validation is performed to assess model performance.

## Prediction
- A sample observation is provided to test the prediction function.

