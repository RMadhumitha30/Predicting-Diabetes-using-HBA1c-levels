# 🧬 Predicting Diabetes Using HbA1c Levels with Machine Learning (2024–2025)

This project leverages machine learning algorithms to predict the likelihood of diabetes based on **Hemoglobin A1c (HbA1c)** levels. HbA1c is a crucial indicator that reflects the average blood glucose levels over the past 2–3 months and is widely used in the diagnosis and management of diabetes.

---

## 🎯 Objective

To develop a predictive model that classifies individuals as diabetic or non-diabetic using HbA1c values, enhancing early detection and supporting medical professionals with data-driven insights.

---

## 🧠 Key Features

- 📊 **Data Preprocessing** – Cleaned and standardized HbA1c dataset for training and testing.
- 🤖 **Model Training** – Built with multiple ML algorithms (Logistic Regression, Decision Trees, SVM, etc.)
- 📈 **Performance Evaluation** – Assessed using accuracy, precision, recall, F1-score, and confusion matrix.
- 🧪 **User Input Prediction** – Allows real-time predictions based on user-entered HbA1c values.
- 📊 **Visualization** – Charts and plots for understanding model behavior and data distribution.

---

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **Libraries**: 
  - Pandas, NumPy
  - Scikit-learn
  - Matplotlib, Seaborn
  - Jupyter Notebook / Streamlit (for UI)
- **IDE**: VS Code / JupyterLab

---

## 📁 Project Structure

```plaintext
diabetes-prediction-hba1c/
│
├── data/
│   └── hba1c_dataset.csv          # Raw or cleaned data file
├── notebooks/
│   └── diabetes_model.ipynb       # Jupyter notebook with full model workflow
├── app/
│   └── streamlit_app.py           # Optional web app for real-time prediction
├── images/
│   └── confusion_matrix.png       # Graphs and visual outputs
├── README.md
└── requirements.txt
