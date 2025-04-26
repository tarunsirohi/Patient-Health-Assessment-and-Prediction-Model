<p align="center">
  <h1><b>AI-Driven Patient Health Assessment and Prediction for Integrated Smart Ambulance and Hospital Care</b></h1>
</p>

## 🧩 About the Project

The **AI-Driven Patient Health Assessment and Prediction System** is designed to continuously monitor a patient’s vital signs using machine learning techniques.  
It processes real-time medical data such as temperature, heart rate, blood pressure, respiratory rate, and oxygen saturation to classify the patient’s condition into **Normal**, **Severe**, or **Critical**.

By detecting early warning signs of health deterioration, the system provides timely alerts to medical staff, ensuring faster interventions and improved healthcare outcomes.

## 🎯 Problem Statement

> In critical healthcare scenarios, manual monitoring of vital signs can cause human errors and delays.  
This project develops an AI-driven monitoring system that classifies patient conditions in real time, enabling accurate, data-driven medical decisions.

## 🛠️ Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - Scipy
  - Openpyxl
- **Tools**:
  - Jupyter Notebook
  - VS Code
  - Git & GitHub
  - Excel
  - Joblib (for model saving)

## 📚 Dataset Information

- Source: Kaggle Health Monitoring Dataset
- Parameters: Temperature, Heart Rate, Blood Pressure (Systolic/Diastolic), Respiratory Rate, Oxygen Saturation, Blood pH, Condition Label (Normal, Severe, Critical)
- Data Handling: Missing value imputation, normalization, outlier removal

## 🧠 Machine Learning Models Used

- Random Forest Classifier
- Decision Tree Classifier
- Support Vector Machine (SVM)
- Naive Bayes Classifier
- Logistic Regression
- **Stacking Classifier** (Best model)

The final model used a Stacking Ensemble, achieving better generalization by combining predictions from multiple models.

## 🚀 Key Features

- Continuous monitoring of patient vital signs
- Early detection of severe or critical conditions
- Real-time alerts for doctors and emergency teams
- Integration-ready with IoT devices and wearables
- Supports remote monitoring and healthcare optimization
