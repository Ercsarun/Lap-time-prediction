# Lap Time Prediction using Machine Learning 🏎️

## 📌 Problem Statement

In racing environments, lap time depends on multiple performance variables including fuel load, tire wear, track type, and driver aggression. Accurate lap time prediction enables better race strategy planning and performance optimization.

This project builds a regression-based performance model to estimate lap time under varying race conditions.

---

## 🏁 Business Context

Race engineers must:

- Optimize pit strategy
- Estimate race pace
- Adjust setup parameters
- Predict performance under varying conditions

This project simulates a race performance modeling system.

---

## 📊 Dataset

Synthetic dataset (5000 samples) generated using realistic racing physics assumptions:

Features:
- Track Temperature
- Fuel Load
- Tire Wear
- Downforce Level
- Driver Aggression
- Track Type (Street / Circuit / HighSpeed)

Target:
- Lap Time (seconds)

---

## ⚙️ Approach

1. Created synthetic racing performance dataset
2. Encoded categorical track types
3. Compared Linear Regression and Random Forest Regressor
4. Evaluated using RMSE (Root Mean Squared Error)
5. Analyzed feature importance

---

## 📈 Results

Linear Regression RMSE: 1.32 seconds  
Random Forest RMSE: 0.46 seconds  

Random Forest captured nonlinear relationships more effectively.

---

## 🔍 Key Insights

Most influential factors:
- Track Type
- Tire Wear
- Fuel Load

Track characteristics significantly impact lap time variance.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

---

## 🚀 Future Improvements

- Add tire degradation over multiple laps (time series modeling)
- Simulate pit stop strategy optimization
- Deploy as web-based race simulator
