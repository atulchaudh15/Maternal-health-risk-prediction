# 🤰 MaternalCare AI - Maternal Health Risk Prediction System

An intelligent healthcare application that leverages **Machine Learning** to predict **maternal health risk levels** using clinical parameters. The application also provides a **BMI Calculator** and an **Expected Delivery Date (EDD) Calculator** to assist with pregnancy health monitoring.

---

## 📌 Overview

MaternalCare AI aims to support early identification of pregnancy-related health risks by analyzing patient health data through a trained Machine Learning model. The application provides an intuitive web interface built with **Streamlit**, making it easy for healthcare professionals and users to perform quick risk assessments.

---

## ✨ Features

* 🔬 **Maternal Health Risk Prediction**

  * Predicts **Low**, **Mid**, or **High** maternal health risk.
  * Uses a trained **Random Forest Classifier**.
  * Accepts patient health parameters as input.

* ⚖️ **BMI Calculator**

  * Calculates Body Mass Index.
  * Displays BMI category based on standard guidelines.

* 📅 **Expected Delivery Date Calculator**

  * Estimates Expected Delivery Date (EDD) using **Naegele's Rule**.

* 🎨 **Modern Streamlit UI**

  * Clean and responsive interface.
  * User-friendly navigation with sidebar.

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit**
* **Scikit-learn**
* **Pandas**
* **NumPy**
* **Pickle**

---

## 📂 Project Structure

```text
Maternal-health-risk-prediction/
│── app.py
│── Maternal Health Risk Data Set.csv
│── MaternalCare_AI_EDA_Model.ipynb
│── model_comparison.ipynb
│── Intelligent_Software_Defect_Prediction.ipynb
│── rf_model.pkl
│── label_encoder.pkl
│── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/atulchaudh15/Maternal-health-risk-prediction.git
cd MaternalCare-AI
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

If a `requirements.txt` file is not available, install the required packages manually:

```bash
pip install streamlit pandas numpy scikit-learn
```

### 3. Generate the Model

Run the notebook to train the model and generate:

* `rf_model.pkl`
* `label_encoder.pkl`

Place both files in the project root directory.

### 4. Run the Application

```bash
streamlit run app.py
```

---

## 📊 Machine Learning Workflow

* Data Collection
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training
* Model Comparison
* Random Forest Model Selection
* Risk Prediction

---

## 📷 Application Preview

### 🏠 Home Page

> Add screenshot here

```
assets/home.png
```

---

### 🔬 Risk Prediction

> Add screenshot here

```
assets/prediction.png
```

---

### ⚖️ BMI Calculator

> Add screenshot here

```
assets/bmi.png
```

---

### 📅 Delivery Date Calculator

> Add screenshot here

```
assets/edd.png
```

---

## 📈 Future Improvements

* User Authentication
* Patient History Management
* Cloud Deployment
* Model Performance Dashboard
* PDF Report Generation
* Doctor Recommendation System
* Real-time Health Monitoring Integration


---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.

## Author

Atul Chaudhary

https://github.com/atulchaudh15