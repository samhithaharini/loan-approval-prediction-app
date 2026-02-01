# 🏦 Loan Approval Prediction  
### Decision Tree Machine Learning Project with Flask Deployment

An end-to-end **Machine Learning web application** that predicts whether a loan will be **Approved or Rejected** based on applicant details.  
The model is trained using a **Decision Tree Classifier** and deployed using **Flask** with a clean, responsive UI.

---

## 📌 Project Overview

Loan approval is a critical task for financial institutions.  
This project automates loan eligibility prediction using applicant information such as income, education, and credit history.

**Key highlights:**
- Real-world dataset
- Complete ML pipeline
- Decision Tree model
- Flask-based web application
- Responsive UI (Desktop & Mobile)
- Deployment-ready project

---

## 📊 Dataset Information

- **Dataset Name:** Loan Prediction Dataset  
- **Source:** Kaggle  
- **Target Variable:** `Loan_Status`

| Value | Meaning |
|------|--------|
| Y | Loan Approved |
| N | Loan Rejected |

### 🔑 Features Used
- Gender  
- Marital Status  
- Dependents  
- Education  
- Self Employed  
- Applicant Income  
- Coapplicant Income  
- Loan Amount  
- Loan Amount Term  
- Credit History  
- Property Area  

---

## ⚙️ Machine Learning Pipeline

1. Data Loading  
2. Data Cleaning & Missing Value Handling  
3. Encoding Categorical Features  
4. Exploratory Data Analysis (EDA)  
5. Feature Selection  
6. Model Training (Decision Tree Classifier)  
7. Model Evaluation  
8. Model Saving using Pickle  
9. Web App Deployment using Flask  

---

## 🧠 Model Details

- **Algorithm:** Decision Tree Classifier  
- **Library:** Scikit-learn  

**Why Decision Tree?**
- Easy to interpret
- Works well with tabular data
- Suitable for classification problems

---

## 🌐 Flask Web Application

The Flask app allows users to:
- Enter loan applicant details
- Predict loan approval status instantly
- Access the app on **desktop and mobile devices**

### 🎨 UI Features
- Black theme
- Two-column layout (desktop)
- Single-column layout (mobile)
- Centered prediction result
- Screenshot-friendly layout

---

## 🗂️ Project Structure

```text
loan-approval-prediction/
│
├── app.py
├── loan_approval_dt_model.pkl
├── requirements.txt
├── README.md
│
└── templates/
    └── index.html

```
---

### ▶️ Run the Project Locally

1️⃣ Clone the Repository

git clone https://github.com/samhithaharini/loan-approval-prediction.git

cd loan-approval-prediction

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run Flask Application

python app.py

4️⃣ Open in Browser

http://127.0.0.1:5000/

---

## 🧪 Sample Test Case

Gender: Male

Marital Status: Married

Dependents: 0

Education: Graduate

Self Employed: No

Applicant Income: 6000

Coapplicant Income: 2000

Loan Amount: 120

Loan Amount Term: 360

Credit History: Good

Property Area: Urban



### Prediction: ✅ Loan Approved

---

## 🚀 Deployment

This project can be deployed on:


Render (Recommended)

Railway

PythonAnywhere

---

## 🛠️ Technologies Used


Python

Pandas

NumPy

Scikit-learn

Flask

HTML5

CSS3

Git & GitHub

---
