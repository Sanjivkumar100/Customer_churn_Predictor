# Customer_churn_Predictor

This project predicts whether a customer is likely to **churn** (leave the company) based on key attributes like contract type, tenure, payment method, and monthly charges. It uses **machine learning models** trained on the [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn) and is deployed using **Gradio** for an interactive web interface.

---

## 🔍 Problem Statement

Telecom companies often face customer churn, which directly impacts revenue. By predicting churn, businesses can take proactive retention actions. This project builds a **classification model** to identify potential churners and provides an **interactive UI for live predictions**.

---

## 🧠 Models Used

- ✅ Logistic Regression  
- ✅ Decision Tree  
- ✅ Random Forest  
- ✅ K-Nearest Neighbors (KNN)  
- ✅ Support Vector Machine (SVM)

> 🔬 **Best Model**: KNN (Accuracy = 80.2%)  
> 🎯 Logistic Regression gave the **best churn recall** (0.54)

---

## 📊 Features Used (Label Encoded)

| Feature         | Description                                |
|----------------|--------------------------------------------|
| `TotalCharges`  | Total amount billed to customer            |
| `MonthlyCharges`| Current monthly charges                    |
| `tenure`        | Number of months the customer has stayed   |
| `Contract`      | Type of contract (e.g., month-to-month)    |
| `PaymentMethod` | Payment method used                        |
| `OnlineSecurity`| Whether security add-on was subscribed     |
| `TechSupport`   | Whether tech support add-on was subscribed |
| `gender`        | Gender of the customer                     |

---

## 🚀 Deployment (Gradio)

An interactive UI built with [Gradio](https://gradio.app/) allows users to:
- Select feature values from dropdowns
- Get an instant churn prediction
- Easily test different customer scenarios
