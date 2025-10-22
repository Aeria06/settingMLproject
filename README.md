


Student Exam Performance Predictor

A machine learning project that predicts student exam scores based on demographic and educational features, with a web interface for interactive predictions.

🚀 Project Overview

This project combines machine learning with a frontend web application:

Backend (ML): Uses a regression model to predict student exam performance based on features like gender, parental education, lunch type, test preparation, and previous scores.

Frontend: A responsive HTML form to input student data and get real-time predictions.

⚡ Features

Predict student exam performance using multiple ML models:

Random Forest, Gradient Boosting, Decision Tree

XGBoost, CatBoost, AdaBoost, Linear Regression

Hyperparameter tuning using GridSearchCV.

Save and load trained models with Pickle.

Interactive Flask web interface.

Stylish single-page frontend with HTML & CSS.

Display predicted results instantly.

Installation

Clone the repository:

git clone https://github.com/yourusername/student-exam-predictor.git
cd student-exam-predictor


Create and activate a virtual environment:

python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate


Install dependencies:

pip install -r requirements.txt


Run the Flask app:

python app.py


Open your browser and go to:

http://127.0.0.1:5000

Usage

Enter student details such as gender, race/ethnicity, parental education, lunch type, test preparation course, and scores.

Click Predict your Maths Score.

Get the predicted performance instantly on the same page.

Folder Structure
├── artifacts/                  # Trained models and processed data
├── notebook/                   # Raw datasets
├── src/
│   ├── components/             # Data ingestion, transformation, model training
│   ├── utils.py                # Helper functions (save/load objects, evaluate models)
│   ├── logger.py               # Logging utility
│   └── exception.py            # Custom exception handling
├── templates/                  # HTML frontend templates
│   └── home.html
├── app.py                      # Flask application
├── requirements.txt            # Python dependencies
└── README.md


SAMPLE VIEW:
<img width="1189" height="888" alt="image" src="https://github.com/user-attachments/assets/8f6ff6a2-0698-49fa-8809-51d445949fa1" />
<img width="427" height="119" alt="image" src="https://github.com/user-attachments/assets/168fc1bf-863e-4bf9-ad5b-4579e0fa9ff2" />
<img width="1133" height="244" alt="image" src="https://github.com/user-attachments/assets/00a29773-4925-4eac-aff5-b272ed9001bf" />
THE LOGS WERE SAVED 
<img width="1263" height="277" alt="image" src="https://github.com/user-attachments/assets/4f52fc17-8a0f-434c-91b5-3864fef6e6bc" />


