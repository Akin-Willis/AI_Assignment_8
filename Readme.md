# Assignment 8: Supervised Learning Classification

## Project Description
This project demonstrates supervised machine learning classification
using the Heart Disease Cleveland UCI dataset from Kaggle.
The goal is to predict whether a patient has heart disease or not
based on clinical features.

## Dataset
- Name: Heart Disease Cleveland UCI
- Source: Kaggle
- Target column: condition (0 = no disease, 1 = disease)
- Features: age, sex, cp, trestbps, chol, fbs, restecg,
  thalach, exang, oldpeak, slope, ca, thal

## Requirements
The following libraries are required to run this notebook:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- mlxtend
- missingno

## How to Set Up and Run the Notebook

Step 1
Open Google Colab at https://colab.research.google.com

Step 2
Upload the notebook file to Colab or open it from GitHub.

Step 3
Upload the dataset file heart_cleveland_upload.csv to Colab
using the Files panel on the left side.

Step 4
Run each cell from top to bottom in order.

Step 5
Make sure all outputs are visible before saving as PDF.

## Notebook Structure
1. Load Dataset and EDA
2. Basic EDA and Statistical Analysis
3. Data Cleaning and Preprocessing
4. Data Visualisation
5. Model Training - KNN Classifier
6. Model Performance Analysis
7. ROC Curve and AUC Score
8. Hyperparameter Tuning with GridSearchCV
