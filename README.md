# 🩺 Diabetes Prediction using SVM

This project demonstrates how to analyze and model the **Diabetes dataset** using Python and popular data science libraries.  
It includes data preprocessing, exploratory steps, and a foundation for building a Support Vector Machine (SVM) classification model.

---

## 📚 Table of Contents
- [About the Project](#about-the-project)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Code Overview](#code-overview)
- [How to Run](#how-to-run)
- [Output](#output)
- [Next Steps](#next-steps)

---

## 🧠 About the Project
The goal of this project is to:
- Load and explore the **diabetes dataset**
- Prepare data for machine learning
- Build a Support Vector Machine (SVM) model for prediction
- Evaluate model accuracy

This serves as a starting point for beginners learning **Machine Learning with Python**.

---

## 🛠️ Technologies Used
- **Python 3.x**
- **pandas** – Data manipulation
- **numpy** – Numerical operations
- **scikit-learn (sklearn)** – Machine Learning framework

---

## 📊 Dataset
The dataset used is **`diabetes.csv`**, which contains medical and diagnostic measurements used to predict diabetes presence.

Example columns may include:
- Pregnancies  
- Glucose  
- BloodPressure  
- SkinThickness  
- Insulin  
- BMI  
- DiabetesPedigreeFunction  
- Age  
- Outcome (0 = Non-diabetic, 1 = Diabetic)

> 🗂️ Make sure to place `diabetes.csv` in the same directory as the script.

---

## 💻 Code Overview


# Load the dataset
diabetes = pd.read_csv('diabetes.csv')

# Display first few records
diabetes.head()
