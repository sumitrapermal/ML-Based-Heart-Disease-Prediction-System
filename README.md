🫀 Heart Disease Prediction System Using Machine Learning

A Machine Learning–based Heart Disease Prediction Web Application developed using Python, Streamlit, and Scikit-learn.
The system predicts whether a person has a high or low risk of heart disease based on clinical and health parameters.

🚀 Project Overview

Heart disease is one of the leading causes of death worldwide. Early detection can help in timely treatment and prevention.
This project uses a K-Nearest Neighbors (KNN) machine learning model to analyze patient data and predict heart disease risk through an interactive web interface.

✨ Features
🫀 Heart disease risk prediction (High / Low)
📊 Interactive and user-friendly Streamlit UI
🤖 Machine Learning model (KNN Classifier)
📈 Feature scaling using StandardScaler
🧠 One-hot encoding for categorical features
⚡ Real-time prediction

🛠️ Technologies Used
Python
Streamlit
Pandas
NumPy
Scikit-learn
Joblib

📂 Project Structure
HeartDisease-Prediction/

│
├── app.py                         # Streamlit web application
├── heartdiseaseprediction.ipynb   # Model training notebook
├── KNN_heart.pkl                  # Trained KNN model
├── scaler.pkl                     # StandardScaler object
├── columns.pkl                    # Model input columns
├── README.md


📊 Input Parameters
The model predicts heart disease risk based on the following inputs:
Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol
Fasting Blood Sugar
Resting ECG
Maximum Heart Rate
Exercise-Induced Angina
Oldpeak (ST Depression)
ST Slope

How to Run the Project:
1️⃣ Clone the Repository
git clone https://github.com/your-username/HeartDisease-Prediction.git
cd HeartDisease-Prediction

2️⃣ Install Required Libraries
pip install streamlit pandas numpy scikit-learn joblib

3️⃣ Run the Streamlit App
streamlit run app.py

🧠 Machine Learning Details:
Algorithm Used: K-Nearest Neighbors (KNN)
Preprocessing Steps:
Handling categorical data using One-Hot Encoding
Feature scaling using StandardScaler
Model Persistence: Joblib

📌 Prediction Output:
⚠️ High Risk of Heart Disease
✅ Low Risk of Heart Disease














