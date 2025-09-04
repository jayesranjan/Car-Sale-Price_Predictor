# 🚗 Car Price Predictor

This project is a **Machine Learning model** that predicts the selling price of used cars based on various features such as brand, year, mileage, fuel type, transmission, and more.  
The final model uses **XGBoost Regressor** for high accuracy in predicting prices.

## Dataset Description

The dataset used in this project contains details of cars and their selling prices.  
It includes manufacturer details, specifications, and usage parameters to help predict the resale value of a car.

- **Size of dataset:** ~8,100 records  

**Features:**
- **Name**: Brand and model of the car.    
- **Year**: The year of manufacture (used to calculate car age).  
- **Kilometers_Driven**: Total distance driven by the car (in KM).  
- **Fuel_Type**: Type of fuel (Petrol, Diesel, CNG, etc.).  
- **Transmission**: Type of transmission (Manual/Automatic).  
- **Owner_Type**: Ownership status (First owner, Second owner, etc.).  
- **Mileage**: Company-claimed mileage (in kmpl or km/kg).  
- **Engine**: Engine displacement (in cc).  
- **Power**: Maximum engine power (in bhp).  
- **Seats**: Seating capacity of the car.  
- **Seller_Type**: Who is the seller(Individual, Dealer or Trustmark Dealer)
- **Price** *(Target)*: Selling price of the used car (in INR Lakhs).  


## ✨ Features
- Exploratory Data Analysis (EDA) with visualizations (Seaborn, Matplotlib).  
- Feature Engineering & Data Preprocessing (encoding, scaling).  
- Tried multiple ML models (Linear Regression, Random Forest, Extra Trees).  
- Final Model: **XGBoost Regressor**.  
- Model evaluation using R², RMSE, and Relative RMSE (%).  
- Saved trained model with `pickle` for deployment.  


## ⚙️ Tech Stack
- **Python**  
- **Pandas, NumPy** – Data handling  
- **Seaborn, Matplotlib** – Data visualization  
- **Scikit-learn** – Preprocessing, evaluation  
- **XGBoost** – Final regression model  


## 📊 Results

- ✅ Built and trained multiple ML models (Linear Regression, Random Forest, Extra Trees, XGBoost).  
- ✅ Final Model: **XGBoost Regressor**.  
- ✅ Achieved **R² Score: ~0.93** on test data.  
- ✅ Achieved **RMSE: ~123,624**.  
- ✅ Relative RMSE: **~23%** compared to mean car price (~₹5.26 Lakhs).  
- ✅ Demonstrated that XGBoost significantly outperformed baseline models.  
- ✅ Successfully saved and exported trained model using **Pickle** for deployment.  


## 🌟 Key Highlights

- 📌 **End-to-End Machine Learning Project** – from data preprocessing and EDA to model training and evaluation.  
- 📌 Implemented multiple models and selected **XGBoost Regressor** as the best performer.  
- 📌 Achieved **R² score ~0.93** with **Relative RMSE ~23%**.  
- 📌 Built reusable code structure for scalability and deployment.  
- 📌 Exported the trained model with **Pickle** for real-world applications.  
- 📌 Prepared for integration with a web app (Streamlit/Flask) for interactive predictions.  
