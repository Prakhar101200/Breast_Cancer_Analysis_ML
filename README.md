# Breast_Cancer_Analysis_ML
# Breast Cancer Detection Project

## Overview

This project focuses on predicting the diagnosis of breast cancer (Malignant or Benign) using machine learning. The dataset used for this project contains features computed from digitized images of cell nuclei.

## Dataset Details

- **Source:** The Breast Cancer dataset is sourced from the University of California, Irvine machine learning repository.
- **Features:** The dataset contains 30 real-value features computed from digitized images of cell nuclei.
- **Target Variable:** The target variable is the diagnosis (Malignant or Benign).

## Approach

### 1. Data Loading and Exploration

- Loaded the Breast Cancer dataset from the UCI machine learning repository.
- Explored the distribution of the target variable (diagnosis) and features.
- Utilized visualizations (histograms, box plots, heatmaps, density plots to understand relationships between variables.

### 2. Model Selection and Training

- Chose the XGBoost Classifier for its versatility and robustness.
- Split the dataset into training and testing sets.
- Trained the XGBoost model on the training set.
- Evaluated the model using accuracy.

### 3. Making Predictions

- Used the trained XGBoost model to predict the diagnosis for a single test record.
- Displayed the predicted class (Malignant or Benign).

## Challenges Faced and Solutions

1. Selecting the right model
   - Experimented several machine learning algorithms to gain the highest accuracy score possible. Thus, chose the XGBosst Classifier.

2. Changing the Data_type of the target variable
   - Having the target variable datatype as object was a challenge faced and to solve this, we applied labelencoder model to change the categorical data into binary format.
     
## Conclusion

This breast cancer detection project utilized a XGBoost Classifier to predict diagnoses based on features extracted from cell nuclei images. The project involved thorough data exploration, model training, and evaluation, along with addressing specific challenges related to dataset characteristics.

## Credits

- The Breast Cancer dataset is sourced from the University of California, Irvine machine learning repository for uploading the dataset.
- Eduonix fro providing the training and guidance to complete this machine leraning project.


