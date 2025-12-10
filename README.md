🩺 Diabetes Prediction Using Machine Learning

A complete end-to-end machine learning project that predicts whether a person is diabetic based on medical diagnostic measurements.
This project demonstrates the full ML workflow — from data preprocessing to real-time prediction — implemented using Python and scikit-learn.

🚀 Project Overview

This project uses the PIMA Diabetes Dataset to build a classification model that predicts the likelihood of diabetes using health parameters such as glucose level, BMI, pregnancies, insulin, and more.

The model includes:
Clean data preprocessing pipeline
Feature scaling using StandardScaler
Training and evaluation of multiple ML algorithms
A real-time predictive system for user input
Fully reproducible code in Jupyter/Google Colab
This project highlights practical ML skills essential for real-world applications and technical interviews.

🧠 Key Features

✔ End-to-end ML workflow

✔ Clean, reproducible code with explanations

✔ Standardized input pipeline to avoid feature mismatch errors

✔ Real-time prediction system using trained model

✔ Tested with Logistic Regression, SVM, and Random Forest

✔ Beginner-friendly and interview-friendly structure

🛠 Tech Stack

Python

NumPy, Pandas

Matplotlib / Seaborn

Jupyter Notebook / Google Colab

📊 Model Workflow

Load Dataset (PIMA Diabetes dataset)

Exploratory Data Analysis

Handle missing values & outliers

Split data into train & test sets

Apply StandardScaler to numeric features

🔍 Sample Prediction Code 

input_data = (5,166,72,19,175.25,8.0,587,51)

columns = ['Pregnancies','Glucose','BloodPressure','SkinThickness',
           'Insulin','BMI','DiabetesPedigreeFunction','Age']

input_df = pd.DataFrame([input_data], columns=columns)

std_data = scaler.transform(input_df)

prediction = classifier.predict(std_data)

print("Diabetic" if prediction[0] == 1 else "Not Diabetic")

📈 Results

Achieved strong and stable classification performance

Real-time prediction works with any user input

Consistent preprocessing ensures reliable output

🧪 What This Project Demonstrates

This project showcases my ability to:

Build ML models from scratch

Create clean preprocessing pipelines

Avoid common ML pitfalls (like mismatched feature names)

Implement deployable prediction logic

Work with healthcare-related datasets

Present ML results in a clear and structured way

📚 Future Improvements

Add a GUI using Tkinter/Streamlit

Implement a full Flask API

Try XGBoost / Hyperparameter tuning

Improve accuracy with advanced preprocessing

Add confusion matrix visualization
Train multiple ML models
Evaluate using accuracy & F1-score
Build a predictive system for user inputs
