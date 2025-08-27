🩺 Disease Prediction (Heart Disease)
📌 Overview

This project predicts the likelihood of heart disease using machine learning models.
It involves data preprocessing, exploratory data analysis (EDA), model training, evaluation, and deployment-ready model saving.
Two models were tested — Logistic Regression and Random Forest Classifier — with performance compared.

📂 Dataset

Source: Kaggle – Heart Disease Data

File used: heart_disease_uci.csv

Includes patient health attributes (age, cholesterol, chest pain type, blood pressure, etc.)

⚙️ Tech Stack / Requirements

Install dependencies with:

pip install -r requirements.txt


Main Libraries:

pandas, numpy

matplotlib, seaborn

scikit-learn (Logistic Regression, Random Forest, preprocessing, metrics)

joblib (for saving models)

▶️ How to Run

Clone the repository

git clone https://github.com/username/disease-prediction.git
cd disease-prediction


Open Jupyter Notebook

jupyter notebook


Run the notebook step by step:

Load dataset

Preprocess (cleaning, encoding, scaling)

Train models

Evaluate performance

Save trained model

Predict on new data

Upload a CSV file with patient data

The saved Random Forest model (heart_rf_model.pkl) + scaler (scalar.pkl) will generate predictions

📊 Results

Exploratory Data Analysis (EDA)

Histograms for feature distributions

Correlation heatmap of numerical features

Feature importance ranking (Random Forest)

Model Performance:

Logistic Regression: Reported accuracy & classification metrics

Random Forest Classifier: Higher accuracy and better feature importance insights

Confusion matrix heatmaps for both models

🚀 Future Improvements

Deploy as a Flask/Django web app for real-time prediction

Add cross-validation for more robust evaluation

Try additional models (XGBoost, Neural Networks)

Hyperparameter tuning for Random Forest
