# Diabetes Readmission Prediction

## Project Overview

This project analyzes hospital records of patients diagnosed with diabetes to predict whether they are likely to be readmitted. The goal is to compare machine learning models and determine which provides the most accurate predictions for hospital readmission.

## Dataset

The dataset contains hospital records for diabetic patients including demographic information, diagnoses, number of medications, and previous hospital visits. The target variable indicates whether a patient was readmitted after discharge using 30 days as a benchmark.

## Methods

The following machine learning models were used and compared:

* Logistic Regression
* Random Forest

The workflow includes:

* Data cleaning and preprocessing
* Feature encoding
* Train/test splitting
* Model training
* Model evaluation using classification metrics

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Results

The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. Random Forest performed better overall in predicting patient readmission. The model was recall optimized so it is less likely to miss someone who would have benefitted from extra care.

## How to Run

Open the notebook in Google Colab using the **Open in Colab** button at the top of the notebook to run the code and reproduce the results.

