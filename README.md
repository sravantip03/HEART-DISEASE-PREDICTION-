# HEART-DISEASE-PREDICTION-
A machine learning web application that predicts heart disease using patient health data. Built with Python, Flask, Machine Learning, HTML, CSS, JavaScript, and SQLite, with prediction history and explainability features.

# HeartHealth AI 

## Project Description

HeartHealth AI is a machine learning-based web application that predicts the possibility of heart disease using patient health data. It provides risk prediction, explainable AI, prediction history, medical report analysis, and heart health recommendations.

The application is developed using Python, Django, Machine Learning, HTML, CSS, JavaScript, and SQLite.

## Features

- Heart disease risk prediction using machine learning.
- Patient assessment form with health-related inputs.
- Explainable AI using SHAP.
- Medical report upload and data extraction.
- Personalized heart health recommendations.
- AI health assessment assistant.
- Prediction history and assessment comparison.
- Downloadable PDF assessment reports.
- Heart health educational modules.
- User registration, login, and profile management.

## Technologies Used

**Frontend:** HTML, CSS, JavaScript, Django Templates

**Backend:** Python, Django

**Machine Learning:** Scikit-learn, Pandas, NumPy

**Explainable AI:** SHAP

**Database:** SQLite

**PDF Report Generation:** ReportLab

**Model Storage:** Joblib

## Machine Learning Algorithms

The project compares the following machine learning algorithms:

- Logistic Regression
- Random Forest
- Gradient Boosting

The models are trained and evaluated to select a suitable model for heart disease prediction.

## Dataset

The project uses a heart disease dataset containing patient health-related attributes.

The model uses the following features:

- Age
- Gender
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression

The dataset is stored in the `machine_learning/dataset/` folder.

## Explainable AI

HeartHealth AI uses SHAP (SHapley Additive exPlanations) to explain the model's prediction.

It helps users understand how different patient health parameters contribute to the prediction.

## Project Structure

- `accounts/` – User registration, login, and profile management.
- `assistant/` – AI health assessment assistant.
- `core/` – Home and educational pages.
- `explainable_ai/` – SHAP-based explanations.
- `history/` – Prediction history and comparison.
- `machine_learning/` – Dataset, model training, and prediction logic.
- `predictions/` – Patient assessment and prediction.
- `recommendations/` – Heart health recommendations.
- `reports/` – PDF report generation.
- `static/` – CSS, JavaScript, and other static files.
- `templates/` – HTML templates.

## Installation and Setup

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd hearthealth_ai
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

For Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply Database Migrations

```bash
python manage.py migrate
```

### 6. Run the Application

```bash
python manage.py runserver
```

Open the application in your browser:

```text
http://127.0.0.1:8000/
```

## Model Training

The project includes trained machine learning model files.

To train the models again, run:

```bash
python machine_learning/train_models.py
```

## Future Enhancements

- Improve model accuracy using additional validated datasets.
- Enhance medical report extraction.
- Add more health-related visualizations.
- Improve application security and deployment.
- Extend explainability features.

## Disclaimer

HeartHealth AI is an academic and educational project developed for learning and demonstration purposes.

It does not provide a medical diagnosis or replace professional medical advice. Users should consult qualified healthcare professionals for medical decisions.

