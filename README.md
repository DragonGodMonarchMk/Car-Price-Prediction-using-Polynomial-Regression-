# Car-Price-Prediction-using-Polynomial-Regression-
A machine learning project that predicts used car prices based on features such as year, fuel type, seller type, transmission, and mileage. Implemented using Polynomial Regression on multiple datasets from CarDekho and other sources.
# 🚗 Car Price Prediction using Polynomial Regression  

This repository contains a **Machine Learning project** that predicts the selling price of used cars using **Polynomial Regression**.  
The project uses multiple car datasets collected from **CarDekho** and other sources.  

---

## 📌 Project Overview  
Predicting car prices is a crucial task in the automobile industry. The aim of this project is to:  
- Analyze historical car data.  
- Apply **Polynomial Regression** to capture non-linear relationships.  
- Predict the selling price of used cars.  
- Visualize insights for better understanding.  

---

## 📂 Dataset  
The repository contains multiple datasets:  
- `car data.csv`  
- `Car details v3.csv`  
- `CAR DETAILS FROM CAR DEKHO.csv`  

Each dataset includes features like:  
- `Year` – Manufacturing year  
- `Present_Price` – Current ex-showroom price  
- `Driven_kms` – Kilometers driven  
- `Fuel_Type` – Petrol/Diesel/CNG  
- `Seller_Type` – Dealer/Individual  
- `Transmission` – Manual/Automatic  
- `Owner` – Number of previous owners  
- `Selling_Price` – Price at which the car is being sold  

---

## 🛠️ Technologies Used  
- **Python 3**  
- **Jupyter Notebook**  
- **NumPy, Pandas** – Data preprocessing  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – Machine Learning (Polynomial Regression)  

---

## 📊 Model  
- Implemented **Polynomial Regression** to predict selling prices.  
- Trained and tested on multiple datasets.  
- Evaluated performance using metrics like **R² Score** and **Mean Squared Error (MSE)**.  

---

## 🚀 How to Run the Project  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/car-price-prediction.git
   cd car-price-prediction
pip install -r requirements.txt
jupyter notebook car-price-prediction-polynomial-regression.ipynb

📈 Results & Insights
Polynomial Regression outperformed Linear Regression in capturing non-linear price variations.

Significant factors affecting car price:
Manufacturing year
Fuel type
Transmission type
Kilometers driven

📌 Future Work
Implement other models (Random Forest, XGBoost).
Deploy model using Flask / Streamlit for real-time predictions.

Build a web dashboard for better visualization.

