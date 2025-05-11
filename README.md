# Multiple Disease Prediction System

This repository contains a Streamlit-based web application for predicting the likelihood of various diseases, including diabetes, heart disease, and Parkinson's disease. The application uses machine learning models trained on respective datasets to make predictions.

## Features

- **Diabetes Prediction**: Predicts the likelihood of diabetes based on user inputs such as glucose level, blood pressure, and BMI.
- **Heart Disease Prediction**: Predicts the likelihood of heart disease based on user inputs such as age, cholesterol level, and resting blood pressure.
- **Parkinson's Disease Prediction**: Predicts the likelihood of Parkinson's disease based on user inputs such as jitter, shimmer, and other vocal features.

## Install the required dependencies

pip install -r requirements.txt

## Usage
Run the Streamlit app:

streamlit run main.py

Open the URL provided by Streamlit in your browser (usually http://localhost:8501).

Select the disease prediction system you want to use and input the required parameters.

## Datasets
Diabetes Dataset: Contains features like glucose level, blood pressure, and BMI.
Heart Disease Dataset: Contains features like age, cholesterol level, and resting blood pressure.
Parkinson's Disease Dataset: Contains vocal features like jitter and shimmer.

## Model Training
The models are trained using the respective datasets in Jupyter notebooks located in the colab_files_to_train_models directory. Each notebook includes data preprocessing, model training, and evaluation.

Pre-trained Models
Pre-trained models are stored in the saved_models directory:

diabetes_model.sav
heart_disease_model.sav
parkinsons_model.sav
These models are loaded in the Streamlit app for predictions.

## Requirements
The project requires the following Python libraries:

numpy
scikit-learn
streamlit
streamlit-option-menu
Install them using the requirements.txt file.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details. ```
