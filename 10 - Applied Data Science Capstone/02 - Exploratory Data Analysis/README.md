# Exploratory Data Analysis (EDA) Overview

Exploratory Data Analysis is the initial step in any data science project. In the first lab, we will perform EDA using a database, while in the second lab, we aim to determine if data can automatically predict the successful landing of Falcon 9's first stage.

## Lab 1: Database Exploration

- **Objective:** Perform EDA using a database.
- **Focus:** Understand the dataset's structure, characteristics, and initial insights.

## Lab 2: Explore Features for Predicting First Stage Landing

- **Objective:** Explore the data to determine attributes influencing the success of Falcon 9's first stage landing.
- **Features for Prediction:**
  - Some attributes indicate if the first stage can be reused, serving as potential features for machine learning.
  - Success rates have improved since 2013, and launch number can be incorporated as a feature.
  - Different launch sites exhibit varying success rates, contributing to predicting successful landings.
  
### Success Rate Analysis

- **Temporal Trend:**
  - Success rate has shown improvement since 2013.
  
- **Launch Site Impact:**
  - CCAFS LC-40 has a success rate of 60%.
  - KSC LC-39A and VAFB SLC 4E have a success rate of around 77%.
  
- **Combining Attributes:**
  - Overlaying landing outcomes with mass data reveals specific success rates.
  - For example, CCAFS LC-40 has a 100% success rate when mass is above 10,000 kg.

### Attribute Correlation Analysis

- In the lab, we will determine attributes correlated with successful landings.

## Data Preparation for Machine Learning

- **Categorical Variable Transformation:**
  - One-hot encoding will be applied to categorical variables.
  
- **Model Preparation:**
  - The data will be prepared for a machine learning model to predict the success of the first stage landing.

*Note: The exploratory phase involves identifying influential features, understanding success rate trends, and preparing data for machine learning models.*
