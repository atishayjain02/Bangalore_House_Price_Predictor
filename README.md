# Bangalore_House_Price_Predictor
# 🏠 Bangalore House Price Prediction

This project predicts housing prices in Bangalore using machine learning. It includes data cleaning, feature engineering, and building models like Linear Regression, Decision Tree and Random Forest. The goal is to estimate house prices based on features like location, square footage, BHK, and bathrooms.

---

## 📌 Key Features

- Cleaned and processed real estate data
- Converted ranges like "1000-1200 sqft" into average values
- Extracted `bhk` from `size`
- Removed outliers based on price per sqft
- Grouped rare locations into a single "other" category
- Built and evaluated:
  - ✅ Linear Regression
  - ✅ Random Forest 
  - ✅ Decision Tree 
- Used RMSE and Cross-validation for evaluation

---
## 📌 Information
- Built and evaluated:
  - ✅ Linear Regression
        Mean RMSE: 136.72363861753297
        Standard deviation: 46.27974703129453
    
  - ✅ Random Forest 
        Mean RMSE: 25.60332280776966
        Standard deviation: 14.788234905008908*
    
  - ✅ Decision Tree
        Mean RMSE: 30.123073929208942
        Standard deviation: 13.818504108786929

## 🔧 Tech Stack

- Python, Pandas, NumPy
- Scikit-learn, Matplotlib
- Jupyter Notebook
- Machine Learning Models 

---

## 🚀 How to Run

1. Clone the repo
2. Install dependencies:
