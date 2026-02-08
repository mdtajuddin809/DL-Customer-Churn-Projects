# 📊 Customer Churn Prediction using Deep Learning

This project predicts **customer churn** using a **Deep Learning model** built with TensorFlow and Scikit-learn.  
A **Streamlit web application** is also included for interactive and real-time churn prediction.

---

## 🚀 Project Description

Customer churn prediction helps businesses identify customers who are likely to stop using a service.  
This project uses historical customer data to train a neural network model that classifies whether a customer will churn or not.

- **Problem Type:** Binary Classification  
- **Target Variable:** Churn (Yes / No)  
- **Approach:** Deep Learning (ANN)

---

## 🧠 Dataset

- **Dataset Used:** Customer Churn Dataset  
- Contains customer demographic, account, and service-related information.
- Data preprocessing includes handling missing values, encoding categorical features, and feature scaling.

---

## 🛠️ Technologies & Libraries Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- TensorFlow / Keras  
- Streamlit  

---

## ⚙️ Model Details

- Neural Network (ANN)
- Activation Functions: ReLU, Sigmoid
- Loss Function: Binary Crossentropy
- Optimizer: Adam
- Evaluation Metric: Accuracy

---

## 🌐 Streamlit Web Application

The Streamlit app allows users to:
- Enter customer details
- Predict customer churn instantly
- Interact with the trained deep learning model

### ▶️ Run the App Locally
```bash
streamlit run app.py
