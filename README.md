**Crop & Fertilizer Prediction - CropFit 🌱**

A web-based application that assists farmers in predicting the optimal crops to grow and the most suitable fertilizers based on soil and environmental parameters using Machine Learning.

**1 About**

CropFit empowers farmers with AI-driven insights for better crop yield and sustainable farming. By entering soil parameters such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall, users can get:

Recommended crop to plant.

Suggested fertilizer for optimal growth.

**2 Features**

User-friendly and responsive web interface.

Machine Learning models for accurate predictions:

Naive Bayes → Crop Prediction

Random Forest → Fertilizer Recommendation

Input validation for realistic soil and weather values.

Mobile-friendly with Bootstrap styling


**3 Clone the repository:**

git clone https://github.com/Eslavathanil/Crop-Fertilizer-Prediction.git
cd Crop-Fertilizer-Prediction


**4 Install dependencies:**

pip install -r requirements.txt


**5 Run the Flask app:**

python app.py


**6 Open your browser and go to:**

http://127.0.0.1:5000/


**7 Usage**

You will see the Home Page.

Click Get Started to go to the prediction page.

Enter the soil and environmental parameters, then click Predict.

View the predicted crop and recommended fertilizer.

**8 Models**

Naive Bayes (naive_bayes_model.pkl): Predicts the suitable crop based on all parameters.

Random Forest (random_forest_model.pkl): Predicts the recommended fertilizer based on N, P, K.

**9 Technologies**

Python 3.x

Flask (Web Framework)

NumPy, pickle (ML model handling)

HTML, CSS, Bootstrap 5 (Frontend)

Font Awesome Icons

**10 Deployment**

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

**11 Live Demo**

Experience the live demo of the application here:

👉 https://crop-fertilizer-prediction-ilfr.onrender.com

**12 License**

This project is licensed under the MIT License - see the LICENSE file for details.













