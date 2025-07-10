
# Food Delivery Time Prediction 

This project aims to predict the delivery time of food orders using machine learning models like Linear Regression, Random Forest, and XGBoost.

---

## Problem Statement
Restaurants want to predict how long a delivery will take to improve efficiency and customer satisfaction.

---

##  Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Geopy (for calculating distance)
- Jupyter/Google Colab

---

## EDA Highlights
- Longest delivery times are influenced by distance, age, and vehicle type.
- Delivery ratings and order type also impact speed.

---

## Models Used
- Linear Regression (baseline)
- Random Forest (best performance)
- XGBoost (optional)

---

##  Evaluation Metrics (Best Model)
- **MAE:** 3.8 mins  
- **RMSE:** 4.5 mins  
- **R² Score:** 0.89  

---

##  Key Insights
- Distance is the strongest predictor of time taken.
- Motorbikes are faster than bicycles.
- Type of order (e.g., buffet vs snacks) influences delay.

---

## Project Structure

```
food-delivery-time-prediction
 ┣ 📜food_delivery_model.ipynb
 ┣ 📜dataset.xlsx
 ┣ 📜README.md
 ┗ 📜requirements.txt
```

---

##  Future Work
- Add live prediction using Streamlit
- Deploy via Flask API
