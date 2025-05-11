# Multiple Disease Prediction System

This repository contains a Streamlit-based web application for predicting the likelihood of various diseases, including diabetes, heart disease, and Parkinson's disease. The application uses machine learning models trained on respective datasets to make predictions.

## Features

- **Diabetes Prediction**: Predicts the likelihood of diabetes based on user inputs such as glucose level, blood pressure, and BMI.
- **Heart Disease Prediction**: Predicts the likelihood of heart disease based on user inputs such as age, cholesterol level, and resting blood pressure.
- **Parkinson's Disease Prediction**: Predicts the likelihood of Parkinson's disease based on user inputs such as jitter, shimmer, and other vocal features.
- **Breast Cancer Prediction**: Predicts the likelihood of breast cancer based on user inputs such as mean radius, mean texture, and other features.


## Requirements
The project requires the following Python libraries:

- numpy
- scikit-learn
- streamlit
- streamlit-option-menu

Install them using the requirements.txt file.

## Install the required dependencies
```
pip install -r requirements.txt
```
## Usage
Run the Streamlit app:
```
streamlit run main.py
```
Open the URL provided by Streamlit in your browser (usually http://localhost:8501).

Select the disease prediction system you want to use and input the required parameters.

## Datasets
- Diabetes Dataset: Contains features like glucose level, blood pressure, and BMI.
- Heart Disease Dataset: Contains features like age, cholesterol level, and resting blood pressure.
- Parkinson's Disease Dataset: Contains vocal features like jitter and shimmer.
- Breast Cancer Dataset: Contains features like mean radius, mean texture, mean perimeter, and mean area.

## Model Training
The models are trained using the respective datasets in Jupyter notebooks located in the colab_files_to_train_models directory. Each notebook includes data preprocessing, model training, and evaluation.

## Pre-trained Models
Pre-trained models are stored in the saved_models directory:

- diabetes_model.sav
- heart_disease_model.sav
- parkinsons_model.sav
- breast_cancer_model.sav

These models are loaded in the Streamlit app for predictions.


## License
This project is licensed under the MIT License. 
