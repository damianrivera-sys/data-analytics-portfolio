# 🚀 Predictive Maintenance for Aircraft Engines (NASA CMAPSS)

## 📌 Overview
This project develops a machine learning model to predict the **Remaining Useful Life (RUL)** of aircraft engines using multivariate sensor data. The dataset is based on simulations developed by NASA, widely used in predictive maintenance research.

## 🎯 Business Problem
Unplanned equipment failures in aviation lead to high maintenance costs, unexpected downtime, and operational inefficiencies. Companies need reliable ways to anticipate failures before they occur.

## 💡 Solution
We build a predictive model that:
- Estimates how many cycles remain before engine failure
- Learns degradation patterns from historical sensor data
- Enables proactive and cost-efficient maintenance strategies

## ⚙️ Methodology
- Data preprocessing and cleaning
- RUL calculation and target definition
- Sensor selection (removal of low-value signals)
- Normalization per engine unit
- Model training using **Gradient Boosting Regressor**

## 📊 Results
- **Model:** Gradient Boosting Regressor
- **Metric:** Mean Absolute Error (MAE)
- **Performance:** **23.13 cycles**

👉 The model can estimate engine degradation with a relatively low prediction error, making it suitable for real-world maintenance scenarios.

## 📈 Key Insights
The most influential sensors were:
- **sensor_11**
- **sensor_4**
- **sensor_12**
- **sensor_7**
- **sensor_17**

These variables show strong correlation with engine degradation patterns. Feature selection significantly improved model performance.

## 📊 Visualization
*(Insert your `images/feature_importance.png` here)*

## 🧰 Tech Stack
- Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## 🚀 Potential Applications
- Predictive maintenance in aviation
- Industrial equipment monitoring
- Manufacturing systems optimization

## 📂 Project Structure
