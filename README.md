# Taxi-Fare-Finder-Pro
This project builds a machine learning model to predict taxi fare amounts based on trip information like pickup and drop-off coordinates, passenger count, and datetime features. It is part of the "Taxi Fare Guru: Total Amount Prediction Challenge" on Kaggle.

# 🚕 Taxi Fare Finder Pro: A Predictive Analytics Project

This project presents a comprehensive machine learning analysis focused on predicting taxi fare amounts based on ride-specific parameters. The objective is to build an efficient fare prediction model that can be integrated into ride-hailing platforms to ensure pricing transparency, enhance customer satisfaction, and support operational optimization.

---

## 🛠️ Tools Used

- **Python (Jupyter Notebook)**
- **Pandas & NumPy** – Data manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-learn** – Machine learning models  
- **Regression Metrics** – RMSE, MAE, R² Score

---

## 📊 Data Description

- **Dataset**: Publicly available taxi fare dataset  
- **Duration**: Covers multiple months of ride data  
- **Data Points**:
  - Pickup & Drop-off Coordinates  
  - Passenger Count  
  - Trip Distance & Duration  
  - Fare Amount  
- **Observations**: Thousands of individual ride entries

---

## 🔍 Analysis Focus

- Data Cleaning & Outlier Handling  
- Exploratory Data Analysis (EDA)  
- Distance Calculation using Haversine Formula  
- Feature Engineering (hour of day, ride distance, etc.)  
- Model Training with Multiple Regressors  
- Model Evaluation using standard performance metrics

---

## 📌 Key Insights

- Fare amounts are significantly influenced by trip distance and time of day  
- Short-distance trips during peak hours show increased fare variability  
- Optimal performance achieved with **Random Forest Regressor** (low RMSE, high R²)  
- Important features: trip distance, pickup hour, and day of the week

---

## 🧠 Recommendations

- Integrate real-time pricing estimator for customer transparency  
- Implement dynamic pricing based on traffic, distance, and demand  
- Use predictive model to flag potentially anomalous or fraudulent fares  
- Enhance user experience by showing estimated fare ranges before booking

---

## 📈 Outcome

- **Best Model**: Random Forest Regressor  
- **RMSE**: ~2.15 (on test set)  
- **R² Score**: ~0.89  
- Built a reliable model for estimating taxi fares in real-world scenarios

---

## 👨‍💻 Team Members

- **Uday Kiran** – 2451-22-750-006  
- **Pranavi** – 2451-22-750-011  
- **Sharanya** – 2451-22-750-051

---

## 📁 How to Use

1. Clone the repository  
2. Open the Jupyter Notebook  
3. Run all cells to reproduce results  
4. Modify or retrain model as needed with your own data

---

## 📜 License

This project is for educational purposes only.

