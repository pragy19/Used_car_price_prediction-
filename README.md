# 🚗 Used Car Price Prediction

A Machine Learning project to predict **used car prices** based on features such as brand, model, mileage, fuel type, transmission, and accident history.  
Built with **Python**, **scikit-learn**, and **XGBoost**.

---

##  Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)

---

##  Overview
This project estimates used car prices using supervised learning models.  
The workflow includes:
- Data preprocessing & feature engineering
- Exploratory Data Analysis (EDA)
- Model training & evaluation
- Saving the best model and preprocessor
- Predictions on new unseen car data

---

##  Features
- Data cleaning and preprocessing (handling missing values, outliers)  
- Feature engineering: horsepower, engine liters, car age, log transforms  
- Multiple models: Linear Regression, Random Forest, XGBoost  
- Performance evaluation using **RMSE** on the original price scale  
- Save & load trained models with `pickle`  

---

##  Project Structure
Used-Car-Price-Prediction/
- data/  (Dataset files, e.g., `used_cars.csv`)
- notebooks/  (Jupyter notebooks for EDA & experiments)
- src/  (Training & prediction scripts)
- models/  (Saved models: `.pkl` files)
- results/  (Evaluation metrics and plots)
- requirements.txt  (Dependencies)
- README.md  

---

##  Installation
Clone the repository:
```bash
git clone https://github.com/<your-username>/Used-Car-Price-Prediction.git
cd Used-Car-Price-Prediction

pip install -r requirements.txt
