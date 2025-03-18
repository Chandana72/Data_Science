# 🚗 Toyota Corolla Price Prediction using Multiple Linear Regression

## 📌 Objective  
Predict the price of a Toyota Corolla based on multiple factors like age, mileage, fuel type, and more using Multiple Linear Regression (MLR).  

## 📊 Dataset  
The dataset includes the following features:  
- **Age** – Age in years  
- **KM** – Accumulated kilometers on odometer  
- **FuelType** – Petrol, Diesel, or CNG  
- **HP** – Horse Power  
- **Automatic** – Automatic transmission (Yes = 1, No = 0)  
- **CC** – Cylinder Volume (cc)  
- **Doors** – Number of doors  
- **Weight** – Weight in kg  
- **Quarterly_Tax** – Tax paid per quarter  
- **Price** – Offer price in Euros  

## 🧠 Models Used  
- Multiple Linear Regression  
- Lasso Regression  
- Ridge Regression  

## 🔍 Techniques Used  
- **Normalization & Standardization:**  
  - Normalization scales data to a fixed range (e.g., [0, 1]) using Min-Max Scaling.  
  - Standardization transforms data to have a mean of 0 and a standard deviation of 1 using Z-score transformation.  

- **Handling Multicollinearity:**  
  - Removed highly correlated features  
  - Used **Variance Inflation Factor (VIF)** to detect multicollinearity  
  - Applied **Ridge Regression** to reduce the impact of multicollinearity  

