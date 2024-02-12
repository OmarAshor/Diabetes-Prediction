Diabetes Prediction Model
This repository contains code for building a machine learning model to predict diabetes based on various health parameters. The model is trained on the diabetes.csv dataset.

Dataset
The dataset used for this project is diabetes.csv, which contains information about several health parameters for individuals, including their diabetes status.

Requirements
Python 3
Libraries: numpy, pandas, scikit-learn
Usage
Clone this repository to your local machine.
Ensure you have the required libraries installed.
Run the Python script diabetes_prediction.py.
The script will load the dataset, preprocess it, train a Support Vector Machine (SVM) model, and evaluate its performance.
Finally, the script will provide predictions for a sample input.
Code Structure
diabetes_prediction.py: Main Python script containing the code for data loading, preprocessing, model training, evaluation, and prediction.
diabetes.csv: Dataset file containing the health parameters and diabetes status.
README.md: This file providing an overview of the project and instructions for usage.
Running the Code
To run the code, execute the following command in your terminal:

bash
Copy code
python diabetes_prediction.py
Model Evaluation
The model's accuracy is evaluated using both training and test datasets. The accuracy scores are printed to the console.

Prediction
The script provides an example of how to make predictions using the trained model. You can modify the input parameters to make predictions for different individuals.

