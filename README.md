# Crime Type Prediction in Bangladesh (Machine Learning)

## 📌 Project Overview
This project focuses on predicting the type of crime in Bangladesh using Machine Learning techniques (multi-class classification).

Given incident-related features such as time, location, and environmental context, the model predicts one of the following crime categories:

- Murder  
- Body Found  
- Rape  
- Assault  
- Kidnap  
- Robbery  

---

## 🎯 Objectives
- Build a machine learning model for crime classification  
- Handle imbalanced dataset effectively  
- Compare multiple ML algorithms  
- Evaluate models using Macro F1 Score  
- Identify the best-performing model  

---

## 🧠 Models Used

### Baseline Models
- Logistic Regression  
- Decision Tree  

### Ensemble Models
- Random Forest ⭐ (Best Model)  
- Extra Trees  
- AdaBoost  
- Gradient Boosting  

### Other Models
- K-Nearest Neighbors (KNN)  
- XGBoost  

---

## 📊 Evaluation Metrics
- Accuracy  
- Macro F1 Score (Primary Metric)  
- Weighted F1 Score  
- Confusion Matrix  

---

## 🏆 Key Results
- Best Model: Random Forest  
- Accuracy: ~0.39  
- Macro F1 Score: ~0.37  

### Key Observations:
- Ensemble methods outperformed simple models  
- Class imbalance significantly affects performance  
- Some crime categories are harder to classify  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Handling missing values  
- Encoding categorical variables  
- Feature scaling (where needed)  

### 2. Handling Imbalance
- Resampling techniques  
- Use of class_weight='balanced'  

### 3. Pipeline
Data → Preprocessing → Model Training → Evaluation → Comparison → Best Model Selection  

---

## 📁 Repository Structure

CrimeDataBD/
│
├── data/
│   ├── raw/              # Original dataset
│   └── processed/        # Processed outputs
│
├── notebooks/
│   ├── logistic_regression.ipynb
│   └── random_forest.ipynb
│
├── src/                  # Future scripts
│
├── reports/
│   └── figures/          # Plots and visualizations
│
├── .gitignore
├── requirements.txt
└── README.md

---

## 📂 Dataset Setup (Local)

Place dataset in:

data/raw/Bangladesh-Crime-Dataset.csv  


---

## 🖥️ Environment Setup

Create a virtual environment:
python -m venv .venv  

Activate (Windows PowerShell):
.\.venv\Scripts\Activate.ps1  

Install dependencies:
pip install -r requirements.txt  

---

## 📈 Visualizations
- Model comparison graph (Macro F1)  
- Confusion Matrix  
- Feature Importance (for tree-based models)  

---

## 📌 Key Insights
- Time of day and location significantly influence crime type  
- Ensemble models perform better on structured/tabular data  
- Macro F1 is essential for imbalanced classification  

---

## ⚠️ Limitations
- Moderate performance due to data complexity  
- Class overlap between crime types  
- Limited feature engineering  

---

## 🚀 Future Improvements
- Hyperparameter tuning (GridSearchCV)  
- Advanced balancing (SMOTE)  
- Feature engineering  
- Deep learning models (optional)  

---

## 👥 Team Workflow
- Collaboration via GitHub  
- Separate notebooks to avoid conflicts  
- Modular structure for scalability  

---

## 📚 Course Information
- Course: CSE 445  
- Topic: Crime Type Prediction using Machine Learning  

---

## 👤 Author
Pranesh Majumder Tirtha  
GitHub: https://github.com/praneshtirtha  
Annanta Saharirar
GitHub: 
(https://github.com/AnantoS2708)

---

## ⭐ Final Note
This project demonstrates a complete end-to-end machine learning pipeline, including preprocessing, model comparison, evaluation, and deployment-ready workflow.
