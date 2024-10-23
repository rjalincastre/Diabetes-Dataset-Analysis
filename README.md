# Diabetes Dataset Analysis

## Overview
This project analyzes a diabetes dataset obtained from Mendeley Data, exploring the data through preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning model training. Multiple classification models are applied, with model interpretability.

## Dataset Source
- **Title:** Diabetes Dataset
- **Source:** Mendeley Data ([doi: 10.17632/wj9rwkp9c2.1](https://data.mendeley.com/datasets/wj9rwkp9c2/1))
- **Author:** Ahlam Rashid
- **Description:** The dataset contains information related to diabetes diagnoses, including patient characteristics and diagnostic outcomes.

## Project Structure
1. **Data Loading**
   - The dataset is downloaded using a direct URL via a `wget` command.
  
2. **Data Cleaning**
   - Class labels are inspected for inconsistencies. Five unique classes are initially found, but they are expected to be limited to 'Y', 'N', and 'P' (representing Yes, No, and Prediabetes).
   - Spaces in front of 'Y' and 'N' labels are removed.
   - Duplicate rows are detected and removed.
   - Missing values are checked, and none are found.

3. **Exploratory Data Analysis (EDA)**
   - The analysis involves understanding data distributions and relationships among features.
   - Visualizations include distribution plots and correlation heatmaps.

4. **Feature Engineering**
   - Categorical variables are encoded using label encoding.
   - Min-Max Scaling is applied to normalize the dataset.

5. **Machine Learning**
   - The dataset is split into training and testing sets.
   - Several classification models are trained and evaluated, including:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Naive Bayes
     - Support Vector Classifier (SVC)
     - Decision Tree Regressor
     - Random Forest Classifier
     - XGBoost Classifier
   - Model performance is evaluated using accuracy, precision, recall, and F1-score metrics.
   - Confusion matrices provide a breakdown of predictions for each model.


## Results
- The project demonstrates the application of different classification models to predict diabetes outcomes, with a focus on accuracy.

## Acknowledgments
- Dataset sourced from Ahlam Rashid, Mendeley Data.
