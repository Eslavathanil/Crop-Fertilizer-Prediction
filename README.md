**Crop & Fertilizer Prediction - CropFit 🌱**

A web-based application that assists farmers in predicting the optimal crops to grow and the most suitable fertilizers based on soil and environmental parameters using Machine Learning.

**Table of Contents**

About

Features

Folder Structure

Installation

Usage

Models

Technologies

Deployment

Live Demo

License

**About**

CropFit empowers farmers with AI-driven insights for better crop yield and sustainable farming. By entering soil parameters such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall, users can get:

Recommended crop to plant.

Suggested fertilizer for optimal growth.

**Features**

User-friendly and responsive web interface.

Machine Learning models for accurate predictions:

Naive Bayes → Crop Prediction

Random Forest → Fertilizer Recommendation

Input validation for realistic soil and weather values.

Mobile-friendly with Bootstrap styling

**Folder Structure**
crop_recommendation/
│── static/                     # Static assets (CSS, JS, images, etc.)
│    ├── css/
│    │   ├── home.css           # Styling for home.html
│    │   └── index.css          # Styling for index.html (login/landing)
│    └── images/                # Store all project images here
│         └── (your images here)
│
│── templates/                  # HTML templates (Jinja2 for Flask)
│    ├── home.html              # Homepage (after login, predictions, UI)
│    └── index.html             # Landing/Login page
│
│── dataset/                    # Dataset storage (CSV, Excel, etc.)
│
│── model/                      # Pre-trained ML models
│    ├── naive_bayes_model.pkl  # Saved Naive Bayes model
│    └── random_forest_model.pkl# Saved Random Forest model
│
│── app.py                      # Main Flask application
│── requirement.txt             # Python dependencies
**Installation**

**Clone the repository:**

git clone https://github.com/Eslavathanil/Crop-Fertilizer-Prediction.git
cd Crop-Fertilizer-Prediction


**Install dependencies:**

pip install -r requirements.txt


**Run the Flask app:**

python app.py


**Open your browser and go to:**

http://127.0.0.1:5000/


**Usage**

You will see the Home Page.

Click Get Started to go to the prediction page.

Enter the soil and environmental parameters, then click Predict.

View the predicted crop and recommended fertilizer.

**Models**

Naive Bayes (naive_bayes_model.pkl): Predicts the suitable crop based on all parameters.

Random Forest (random_forest_model.pkl): Predicts the recommended fertilizer based on N, P, K.

**Technologies**

Python 3.x

Flask (Web Framework)

NumPy, pickle (ML model handling)

HTML, CSS, Bootstrap 5 (Frontend)

Font Awesome Icons

**Deployment**

This application is deployed on Render. To deploy your own Flask app on Render, follow these steps:
GitHub
Sign up at Render
 and connect your GitHub account.

Create a new Web Service:

Click on New > Web Service.

Connect your GitHub repository.


Deploy and monitor the build process. Once completed, your app will be live at a onrender.com URL.

For more detailed instructions, refer to the Render Flask Deployment Guide
.

**Live Demo**

Experience the live demo of the application here:

👉 https://crop-fertilizer-prediction-ilfr.onrender.com

**License**

This project is licensed under the MIT License - see the LICENSE file for details.











