# AI-Powered-Disease-Prediction-Personalized-Medical-Recommendation-System-End-to-End-Project-

#  Problem Statement

Early identification of diseases based on symptoms can significantly improve healthcare outcomes. This project builds a machine learning system that predicts diseases based on user-input symptoms and provides personalized recommendations including precautions, medications, workouts, and diet plans.

#  Features

Symptom-based disease prediction (Multi-class classification)
Multiple ML model comparison
Best model selection (Linear SVC)
Personalized recommendations:
Disease Description
Precautions
Medications
Diet Plan
Workout Suggestions
Flask-based interactive web application
Real-time inference

# Machine Learning Pipeline

Data preprocessing
Label encoding

Train-test split (70-30)

Model training:

Support Vector Machine
Random Forest
Gradient Boosting
KNN
Naive Bayes
Model evaluation (Accuracy + Confusion Matrix)
Model serialization using Pickle
Deployment using Flask

#  Model Performance
Model	Accuracy
SVC	 : 100%
Random Forest :	98%
Gradient Boosting	 : 97%
KNN	: 95%
Naive Bayes	: 92%

Final Model Used: Linear SVC

# Tech Stack

1) Python
2) Scikit-learn
3) Pandas & NumPy
4) Flask
5) HTML/CSS
6) Pickle (Model Serialization)

# 📂 Project Structure
│── main.py
│── svc.pkl
│── templates/
│── static/
│── datasets/
│── README.md
⚙️ How to Run
pip install -r requirements.txt
python main.py

Open in browser:

http://127.0.0.1:5000/\

# Sample Input
itching, skin_rash, nodal_skin_eruptions
Output:
Fungal Infection
Description

4 Precautions
Medications
Diet Plan
Workout Plan

