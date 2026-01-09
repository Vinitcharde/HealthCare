# 🏥 HealthCare – Disease Risk Prediction Web App

HealthCare is a web-based mini project that estimates a patient’s disease risk using health-related inputs and a basic machine learning workflow.  
It integrates a simple HTML/CSS/JavaScript frontend with Python-based data analysis and ML experimentation using Jupyter Notebook.

This project is developed as an academic and learning project, demonstrating an end-to-end flow from datasets to analysis, model experimentation, and a web interface.

---

## 📚 Table of Contents

- Overview  
- Features  
- Project Structure  
- Datasets  
- Tech Stack  
- Getting Started  
- How the App Works  
- Currently Learning  
- Future Improvements  
- Author  
- Disclaimer  

---

## 🔍 Overview

This project demonstrates a complete health risk prediction workflow, including:

- Loading real healthcare datasets (heart disease & diabetes)
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Training basic classification models
- A frontend UI that collects patient information and displays a risk message

⚠️ The current frontend uses rule-based client-side logic as a placeholder instead of real-time ML predictions.

---

## ✨ Features

- Web form to collect patient health details:
  - Age  
  - Gender  
  - Blood pressure  
  - Cholesterol  
  - Heart rate  
- Client-side disease risk estimation using JavaScript
- Jupyter Notebook for:
  - Data loading
  - EDA and visualization
  - Machine learning model training
- Clean and responsive UI using vanilla HTML, CSS, and JavaScript

---

## 🗂 Project Structure

HealthCare/
│
├── ML_model_envision.ipynb                     # Jupyter notebook: EDA & ML models
├── diabetes.csv                                # Diabetes dataset
├── heart_statlog_cleveland_hungary_final.csv   # Heart disease dataset
├── index.html                                  # Main frontend page
├── script.js                                   # Client-side logic (risk scoring)
├── style.css                                   # UI styling
└── README.md                                   # Project documentation

---

## 📂 Datasets

- Diabetes Dataset  
  Contains medical parameters related to diabetes risk.

- Heart Disease Dataset  
  Combined Cleveland & Hungary dataset including age, blood pressure, cholesterol, and ECG-related features.

These datasets are used strictly for educational purposes.

---

## 🛠 Tech Stack

Frontend:
- HTML  
- CSS  
- JavaScript  

Data Science & Machine Learning:
- Python  
- NumPy  
- Pandas  
- Scikit-Learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🚀 Getting Started

### Prerequisites

- Git  
- Python 3.x  
- Jupyter Notebook  
- A modern web browser  

---

### Clone the Repository

git clone https://github.com/Vinitcharde/HealthCare.git  
cd HealthCare

---

### Run the Frontend

1. Open the HealthCare folder  
2. Double-click index.html  
   OR  
3. Right-click → Open with → Any modern browser  

---

### Run the Notebook

Install dependencies:

pip install numpy pandas scikit-learn matplotlib seaborn jupyter

Launch Jupyter Notebook:

jupyter notebook ML_model_envision.ipynb

---

## 🧠 How the App Works

1) User Interface  
The frontend collects patient health parameters and explains disease risk in simple language.

2) Client-Side Logic  
script.js handles form inputs, validation, and rule-based disease risk scoring.  
This logic can later be replaced with real ML predictions through a backend API.

3) Machine Learning Workflow  
The notebook performs:
- Data loading and cleaning  
- Exploratory Data Analysis (EDA)  
- Feature preprocessing  
- Training classification models such as Logistic Regression  
- Basic evaluation and insights  

---

## 📚 Currently Learning

- Advanced Excel (dashboards, analysis, automation)
- SQL (joins, optimization, database design)
- Data Structures and Algorithms
- Machine Learning model improvement and evaluation
- AI and Generative AI in healthcare
- Business Intelligence and data visualization tools

---

## 🔮 Future Improvements

- Build a Flask or FastAPI backend for real-time predictions
- Connect frontend to backend using Fetch API
- Add interactive charts and risk visualizations
- Implement user authentication and prediction history
- Deploy the application using GitHub Pages or cloud platforms

---

## 👤 Author

Vinit Charde  

GitHub: https://github.com/Vinitcharde  
Email: vinitcharde24@gmail.com  

---

## ⚠ Disclaimer

This project is developed for educational purposes only.  
It is not a medical diagnostic tool and should not be used for real clinical or healthcare decisions.
