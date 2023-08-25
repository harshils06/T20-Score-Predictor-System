# **T20 Score Predictor**
Dataset: https://www.kaggle.com/veeralakrishna/cricsheet-a-retrosheet-for-cricket?select=t20s

# **Overview**
The T20 Score Predictor System is a machine learning-based project that utilizes the XGBoost algorithm and the Streamlit library to predict scores in T20 cricket matches. This project includes various stages of the pipeline, including data cleaning, data transformation, and feature engineering, to create an accurate score prediction model.

## Table of Contents
### Introduction
### Installation
### Pipeline
###    1) Data Cleaning
###    2) Data Transformation
###    3) Feature Engineering
###    4) Model Training using XGBoost
## Introduction
The T20 Score Predictor System aims to predict the scores of T20 cricket matches using historical match data. By employing the powerful XGBoost algorithm, this project provides an insightful tool for cricket enthusiasts and analysts to estimate the possible scores that teams might achieve in T20 matches.

## Installation
Make sure you have activated your virtual environment (if used).

Run the Streamlit app:
streamlit run app.py
The app will open in your default web browser. You can interact with the app by providing match-related inputs and receiving score predictions.
## Pipeline
### Data Cleaning
The initial step involves cleaning the raw data obtained from reliable cricket sources. This process addresses missing values, handles inconsistencies, and prepares the data for subsequent stages.

### Data Transformation
In this stage, the cleaned data is transformed into a suitable format for feature engineering and model training. The data might be converted into numerical representations, normalized, and split into training and testing sets.

### Feature Engineering
Feature engineering plays a crucial role in enhancing the predictive capabilities of the model. Relevant features are selected, created, or modified to capture the underlying patterns in the data effectively.

### Model Training using XGBoost
XGBoost, a powerful gradient boosting algorithm, is employed to train the score prediction model. The model is trained using the training data prepared in the previous stages.

