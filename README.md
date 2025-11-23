# Diabetes Detector 🩺🤖

A machine-learning based diabetes prediction system built using Python, Pandas, Scikit-learn and Jupyter Notebook.

This project takes health parameters such as glucose level, BMI, age, blood pressure, skin thickness, insulin levels, etc., and predicts whether a person has a high chance of being diabetic.

---

## 🚀 Features
- Cleaned and preprocessed PIMA Diabetes dataset  
- Missing value handling using SimpleImputer  
- Feature scaling using StandardScaler  
- Two ML models trained: Logistic Regression & Random Forest  
- Automatically picks the better model based on ROC-AUC score  
- Interactive prediction (user enters values and model outputs result)  
- Saved model + preprocessing pipeline for future use  
- Screenshots included for verification

---

## 📂 Project Structure

---

## 🧠 Machine Learning Approach

### 1️⃣ Preprocessing Pipeline  
- Replaces missing values  
- Scales features  
- Normalizes input for ML models  

Saved as: `preprocessing_pipeline.joblib`

### 2️⃣ Models Trained  
- Logistic Regression  
- Random Forest Classifier  

The project compares:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  

The model with the **higher ROC-AUC** is saved as the final model.

---

## 🧪 Prediction Demo  
The notebook includes an interactive section where the user inputs:

- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  

The model returns:

---

## 📊 Results  
Full evaluation metrics are inside:
- `ss_cell6_results.png`
- `ss_cell8_prediction.png`

---

## 📄 Documentation  
Full project documentation is included as:

**Diabetes Detector Project - Documentation.pdf**

---

## 🧑‍💻 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Jupyter Notebook  
- Matplotlib  

---

## 🙌 Author
Samriti — for Semester Project (Build Your Own Project)

---


