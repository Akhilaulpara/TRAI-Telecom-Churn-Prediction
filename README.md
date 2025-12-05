![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Streamlit](https://img.shields.io/badge/Framework-Streamlit-red)
![LightGBM](https://img.shields.io/badge/Model-LightGBM-green)
![Status](https://img.shields.io/badge/Status-Active-success)

## 🧠 Overview
The **Telecom Churn Prediction Dashboard** helps identify operator–circle combinations at high risk of subscriber decline.  
The solution combines **LightGBM-based churn modeling** with an **interactive Streamlit dashboard** for trend analysis, risk visualization, and model evaluation.

---

## ✨ Key Features
- 📊 **Exploratory Data Analysis (EDA):** Understand subscription trends by month, region, and operator.  
- 🔍 **Churn Severity Tagging:** Categorizes churn risk as *Stable, Mild, Low, Medium,* or *High*.  
- 🤖 **Machine Learning Model:** Predicts churn using a trained LightGBM model with time-aware features.  
- 🧾 **Model Evaluation:** Displays ROC-AUC, precision, recall, accuracy, and confusion matrix.  
- 📌 **High-Risk Segments:** Highlights operator–circle pairs with the highest predicted churn probability.

---

## 🧰 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, Joblib  
- **Model:** LightGBM  
- **Interface:** Streamlit  

---

## 📘 Dataset Description
The dataset contains monthly subscriber counts for telecom operators across multiple Indian telecom circles.  
Each row represents the subscriber value for a specific **operator × circle × month**.

---

## 📊 Dataset Columns & Descriptions

| Column Name           | Description |
|----------------------|-------------|
| **year**             | Year when the subscriber data was recorded. |
| **month**            | Month corresponding to the recorded subscriber count. |
| **circle**           | Telecom service region/state (circle) where the data belongs. |
| **type_of_connection** | Type of telecom connection such as *wireless* or *wireline*. |
| **service_provider** | Name of the operator providing telecom services in the circle. |
| **value**            | Number of subscribers for that operator in the given month and region. |
| **unit**             | The measurement unit of the subscriber count (typically absolute numbers). |
| **notes**            | Additional comments or metadata associated with the record (may be empty). |

---

