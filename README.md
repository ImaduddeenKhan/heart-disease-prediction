# ❤️ Heart Disease Prediction System

> **Predict your 10-year heart disease risk using Machine Learning & Flask Web App**  

This project is a **Machine Learning-powered web application** that predicts the likelihood of a person developing heart disease within 10 years based on their health data. It combines **data science**, **AI**, and a **user-friendly interface** to make preventive healthcare more accessible.  

---

## 📋 Table of Contents
- [About the Project](#-about-the-project)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Data Features](#-data-features)
- [How It Works](#-how-it-works)
- [Screenshots](#-screenshots)
- [Setup Instructions](#-setup-instructions)

---

## 📖 About the Project
Heart disease is one of the leading causes of death globally. Early detection can **save lives**.  
This project predicts whether a person is at risk of developing heart disease in the next 10 years using **classification algorithms**. The model is integrated into a **Flask web application**, allowing anyone to input their health data and get instant predictions.

**Benefits:**
- Early detection for timely intervention
- Accessible via an easy-to-use web app
- Powered by **Machine Learning** for accurate predictions

---

## ✨ Features
✅ Predicts **10-year heart disease risk**  
✅ Multiple machine learning algorithms tested — **Random Forest** performed best  
✅ **Flask Web App** for user-friendly interaction  
✅ Detailed model evaluation with **confusion matrix & classification report**  
✅ Responsive **Bootstrap-based UI**  
✅ Saves trained models for quick future predictions  

---

## 🛠 Tech Stack

**Programming Language:**
- Python 🐍

**Machine Learning & Data Science:**
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Pickle (for model persistence)

**Web Framework:**
- Flask

**Frontend:**
- HTML, CSS, Bootstrap
- Jinja2 templating

**Development:**
- Jupyter Notebook
- PyCharm

---

## 📊 Data Features

| Feature | Description |
|---------|-------------|
| `male` | Gender: 1 = Male, 0 = Female |
| `age` | Age in years |
| `education` | Education level (later dropped as irrelevant) |
| `currentSmoker` | 1 = Yes, 0 = No |
| `cigsPerDay` | Cigarettes smoked per day |
| `BPMeds` | Blood Pressure Medication (1/0) |
| `prevalentStroke` | History of stroke (1/0) |
| `prevalentHyp` | History of hypertension (1/0) |
| `diabetes` | Diabetes status (1/0) |
| `totChol` | Total cholesterol |
| `sysBP` | Systolic blood pressure |
| `diaBP` | Diastolic blood pressure |
| `BMI` | Body Mass Index |
| `heartRate` | Resting heart rate |
| `glucose` | Blood glucose level |
| **Target** | 10-year CHD risk: 1 = Yes, 0 = No |

---

## ⚙ How It Works
1. **Data Preprocessing** – Missing values handled, scaling applied  
2. **Data Balancing** – Over-sampling to address class imbalance  
3. **Model Training** – Tested Logistic Regression, Decision Tree, Random Forest, SVM, KNN, AdaBoost, Gradient Boosting, XGBoost  
4. **Evaluation** – Accuracy, precision, recall, F1-score  
5. **Model Saving** – Trained model & scaler saved with Pickle  
6. **Web Integration** – Flask app for real-time prediction  



---

## 🚀 Setup Instructions

```bash
# 1. Clone this repository
git clone https://github.com/ImaduddeenKhan/heart-disease-prediction.git
cd heart-disease-prediction

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate      # Mac/Linux
venv\Scripts\activate         # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Flask app
python app.py

# 5. Open in browser
http://127.0.0.1:5000




---

If you want, I can also make a **fancier version with shields.io badges**, animated GIFs, and an **interactive model diagram** so your GitHub visitors get a “wow” effect. That’ll make your project look like a top-tier portfolio piece.
