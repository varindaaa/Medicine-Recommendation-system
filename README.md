# 🩺 HealthPredict – Disease Prediction & Medicine Recommendation System

## 📌 Project Overview
**HealthPredict** is an ML-powered web application that predicts diseases based on user-entered symptoms and provides personalized recommendations including medicines, precautions, and dietary advice.  
The project integrates **Machine Learning**, **Flask backend**, and an **HTML/CSS frontend** to deliver real-time predictions through a simple and interactive interface.

## 🧰 Tools & Technologies
- **Python**
- **Flask**
- **Scikit-learn**
- **Pandas & NumPy**
- **Pickle (for model deployment)**
- **HTML, CSS, Bootstrap**

## 🤖 Machine Learning Workflow
- Performed **data preprocessing**, handled missing values, and encoded symptom–disease data  
- Explored and trained multiple ML models:  
  - Random Forest  
  - Gradient Boosting  
  - Support Vector Classifier (SVC)  
  - K-Nearest Neighbors (KNN)  
  - Multinomial Naive Bayes  
- Hyperparameter tuning for optimal performance  
- Achieved **100% accuracy** on clean dataset  
- Exported final trained model using **Pickle** for real-time usage in Flask  

## 🌐 Web Application Features
- Simple and interactive **Frontend (HTML/CSS/Bootstrap)**  
- Flask-based backend to handle user input and model predictions  
- Displays complete medical insights:
  - Disease Name  
  - Description  
  - Precautions  
  - Recommended Medicines  
  - Diet Suggestions  
- Real-time prediction using the trained ML model  
- User-friendly design with smooth navigation

Dashboard
<img width="959" height="492" alt="Dashboard" src="https://github.com/varindaaa/Medicine-Recommendation-system/blob/main/Dashboard.png"/>

/HealthPredict
│
├── /static
│ ├── css
│ └── images
│
├── /templates
│ ├── index.html
│ └── result.html
│
├── model.pkl
├── app.py
├── dataset.csv
└── README.md
