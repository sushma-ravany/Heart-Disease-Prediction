# Heart Disease Prediction using Gaussian Naive Bayes

## Project Overview

This project predicts the presence of heart disease using patient clinical data and a Gaussian Naive Bayes classification model. The objective is to classify patients into heart disease and non-heart disease categories based on medical attributes such as age, cholesterol level, blood pressure, chest pain type, and maximum heart rate.

## Dataset

The dataset contains patient medical records and a target variable indicating the presence or absence of heart disease.

### Target Variable

* 0: No Heart Disease
* 1: Heart Disease

### Features

* Age
* Sex
* Chest Pain Type (cp)
* Resting Blood Pressure (trestbps)
* Cholesterol (chol)
* Fasting Blood Sugar (fbs)
* Resting ECG (restecg)
* Maximum Heart Rate Achieved (thalach)
* Exercise Induced Angina (exang)
* ST Depression (oldpeak)
* Slope
* Number of Major Vessels (ca)
* Thalassemia (thal)

## Project Workflow

1. Data Loading and Exploration
2. Feature and Target Separation
3. Train-Test Split
4. Gaussian Naive Bayes Model Training
5. Model Evaluation
6. Result Interpretation

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

## Machine Learning Algorithm

### Gaussian Naive Bayes

Gaussian Naive Bayes was selected because the dataset primarily contains continuous numerical medical measurements. 

## Evaluation Metrics

The model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

## Results

* Accuracy: 81.97%
* Correctly Classified Patients: 50 out of 61
* Precision (Heart Disease): 85%
* Recall (Heart Disease): 76%
* F1-Score (Heart Disease): 80%

The model demonstrated reasonably balanced performance across both classes and serves as a baseline for future comparison with more advanced classification algorithms.

## Future Improvements

* Logistic Regression implementation
* Decision Tree Classifier
* Random Forest Classifier
* Hyperparameter Tuning
* Cross Validation
* Feature Selection
* Model Deployment using Streamlit

## Author

Created as part of a machine learning learning project focused on healthcare classification problems and the practical application of Gaussian Naive Bayes.
