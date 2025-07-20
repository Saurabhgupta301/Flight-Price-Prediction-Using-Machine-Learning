# Flight Price Prediction Using Machine Learning

## 📌 Overview
This project focuses on building a **machine learning model** to predict flight ticket prices based on features like departure/arrival time, airline, duration, number of stops, and other relevant factors. The objective is to provide users with price estimates to assist in making **informed flight booking decisions**.

---

## 🔧 How the Project Was Developed

1. **Project Goal & Dataset**  
   - Used a flight fare dataset containing details such as airline name, source/destination, date, time, duration, stops, and price.  
   - The aim was to predict the ticket price using regression techniques.

2. **Data Preprocessing & Feature Engineering**  
   - Converted date/time fields into useful components (e.g., journey day, month, hour).  
   - Handled categorical variables using one-hot encoding.  
   - Managed missing values and cleaned inconsistencies.

3. **Modeling & Evaluation**  
   - Built regression models including **Linear Regression**, **Random Forest**, and **XGBoost**.  
   - Performed hyperparameter tuning using GridSearchCV.  
   - Evaluated performance using metrics like **R² Score**, **MAE**, and **RMSE**.

---

## ✨ Key Insights

| Feature                  | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| ✈️ **Flight Duration**         | Longer flight durations usually led to higher prices                        |
| 🛫 **Departure Time Impact**   | Prices varied based on departure time—early morning flights were cheaper   |
| 🔁 **Number of Stops**         | More stops typically resulted in higher fares                              |
| 🏷️ **Airline Trends**          | Premium airlines charged significantly more than budget carriers           |

---

## 🛠️ Key Skills Used

- **Python Programming** – for scripting, modeling, and automation  
- **Pandas & NumPy** – for data wrangling and transformation  
- **Matplotlib & Seaborn** – for data visualization and EDA  
- **Scikit-learn** – for building and evaluating regression models  
- **XGBoost** – for gradient boosting and model improvement  
- **Feature Engineering** – extracting meaningful features from raw data  
- **Hyperparameter Tuning** – using GridSearchCV for performance optimization

---

## 🎯 Final Outcome
A robust machine learning pipeline that predicts flight prices with reasonable accuracy. The project demonstrates how data-driven models can be used to provide real-time price estimates to users, improving travel planning and cost awareness.

---

> ✅ *Explore the code, test different models, or deploy the prediction logic into a web application for real-time use cases!*

