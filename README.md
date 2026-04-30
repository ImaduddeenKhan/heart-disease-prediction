<div align="center">
  <h1>Heart Disease Risk Predictor</h1>
  <p><strong>Predict 10-year heart disease risk from clinical inputs in seconds.</strong></p>
  <p>A machine-learning powered Flask app that turns patient data into an interpretable risk signal for early screening.</p>

  <p>
    <img alt="Build" src="https://img.shields.io/badge/Build-Not%20configured-lightgrey" />
    <img alt="License" src="https://img.shields.io/badge/License-Not%20specified-lightgrey" />
    <img alt="Python" src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white" />
    <img alt="Flask" src="https://img.shields.io/badge/Flask-Framework-000000?logo=flask&logoColor=white" />
    <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white" />
  </p>

  <p>
    <a href="#-project-overview">Overview</a> •
    <a href="#-installation--setup">Setup</a> •
    <a href="#-project-structure">Structure</a> •
    <a href="#-future-improvements">Roadmap</a>
  </p>
</div>

---

## ⚡ 1-Minute Overview
- **What it does:** Predicts a patient’s 10-year heart disease risk using a trained ML model.
- **Why it matters:** Early risk detection enables preventive action and informed clinical follow-up.
- **Key features:** Web form UI, real-time predictions, trained Random Forest model, saved scaler/model artifacts.
- **Tech stack:** Python, Flask, scikit-learn, NumPy, Bootstrap.

---

## 🚀 Project Overview
This project delivers a clean, production-style demo of a heart disease risk prediction pipeline. A trained model (Random Forest) and scaler are packaged with a Flask web app, allowing users to input health metrics and receive an instant risk classification.

**Note:** This is an educational project and not intended for clinical decision-making.

---

## 🧠 Problem & Solution
**Problem:** Heart disease remains a leading global cause of mortality, and early risk detection is often missed in routine care.  
**Solution:** A lightweight ML system that surfaces a risk signal from common clinical inputs, wrapped in a user-friendly web interface for quick assessment.

---

## ✨ Features
- 🔍 **Instant Risk Prediction** from clinical inputs
- 🧪 **Random Forest Model** with saved artifacts for repeatable inference
- 🧭 **Clean Web UI** built with Bootstrap and Jinja2
- 📦 **Reusable Assets** (model + scaler stored in `Models/`)
- 🗂️ **Training Notebook** included for transparency and iteration

---

## 🛠 Tech Stack
**Core:** Python, Flask, scikit-learn, NumPy  
**UI:** HTML, CSS, Bootstrap, Jinja2  
**Artifacts:** Pickle (`rf_classifier.pkl`, `scaler.pkl`)  
**Data:** Framingham dataset (`datasets_4123_6408_framingham.csv`)

---

## 📸 Screenshots / Demo
- **Local demo:** Run the app and open `http://127.0.0.1:5000`
- **Screenshot:** Add `assets/demo.png` and update the link below.

  ```text
  ![App Screenshot](assets/demo.png)
  ```

---

## ⚙️ Installation & Setup
```bash
# 1. Clone the repository
git clone https://github.com/ImaduddeenKhan/heart-disease-prediction.git
cd heart-disease-prediction

# 2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows

# 3. Install dependencies
pip install flask numpy scikit-learn

# 4. Run the application
python app.py

# 5. Open in browser
http://127.0.0.1:5000
```

**Important:** `app.py` currently loads model artifacts via absolute Windows paths. Update those paths to point to `Models/rf_classifier.pkl` and `Models/scaler.pkl` on your machine.

---

## 📂 Project Structure
```text
heart-disease-prediction/
├── app.py
├── Models/
│   ├── rf_classifier.pkl
│   └── scaler.pkl
├── templates/
│   └── index.html
├── Modeling.ipynb
├── datasets_4123_6408_framingham.csv
└── README.md
```

---

## 🔮 Future Improvements
- Add a REST API endpoint for programmatic predictions
- Introduce model calibration and confidence scores
- Improve data validation and input constraints
- Dockerize for one-command setup
- Add automated tests and CI pipeline

---

## 🤝 Contribution Guidelines
Contributions are welcome! Please open an issue to discuss changes before submitting a PR.  
Keep PRs focused, provide clear descriptions, and include relevant screenshots for UI changes.

---

## 📜 License
No license file is currently provided. If you intend to make this reusable, add a `LICENSE` file and update this section.
