# Water Quality Prediction - RMS

This project aims to predict multiple water quality parameters using machine learning techniques, specifically `MultiOutputRegressor` wrapped around a `RandomForestRegressor`.

---

## 🌍 Overview

Access to clean water is a critical global concern. Accurate prediction of various water quality metrics can help in early detection of pollution and ensure timely intervention.

---

## 📌 In this project, I:

- Collected and preprocessed real-world water quality datasets  
- Used supervised machine learning for multi-target regression  
- Built a pipeline using `MultiOutputRegressor` with `RandomForestRegressor`  
- Evaluated the model using appropriate regression metrics

---

## 🛠️ Technologies Used

- Python 3.12  
- **Pandas**, **NumPy** – Data handling  
- **Scikit-learn** – Machine learning model and evaluation  
- **Matplotlib**, **Seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive experimentation  

---

## 💧 Predicted Water Quality Parameters

The model predicts multiple water quality parameters such as:

- NH4  
- BOD5 (BSK5)  
- Colloids  
- O₂  
- NO₃  
- NO₂  
- SO₄  
- PO₄  
- Cl⁻

---

## 📊 Model Performance

The model was evaluated using:

- R² Score  
- Mean Squared Error (MSE)  

✅ Performance was acceptable across all parameters.
