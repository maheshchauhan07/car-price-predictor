# 🚗 Car Price Prediction Web App

This project is a **Machine Learning** application that predicts the price of second-hand cars based on user input. It includes **data cleaning**, **model training**, and deployment using **Flask** to create an interactive web app.

## 📊 Dataset Overview

The dataset includes information about used cars and contains the following columns:

- `name`: Name of the car (e.g., Maruti Swift, Hyundai i20)
- `company`: Brand or manufacturer of the car
- `year`: Year of manufacture
- `Price`: Selling price of the car (target variable)
- `kms_driven`: Total kilometers driven
- `fuel_type`: Type of fuel (e.g., Petrol, Diesel)

## 🧼 Data Preprocessing

- Removed irrelevant entries and duplicates
- Cleaned text fields (e.g., `kms_driven`)
- Converted data types as needed
- Handled missing values
- Extracted features for training

## 📈 Model Building

- **Train-Test Split** was applied on the cleaned data
- Trained a **Linear Regression model**
- Achieved **accuracy of 92%** on test data

## 🌐 Web App (Flask)

An interactive web app was built using Flask:
- Users enter details: `car name`, `company`, `year`, `kms driven`, and `fuel type`
- The app predicts the expected selling price of the car

## 🛠️ Tech Stack

- **Python**
- **Pandas**, **NumPy** for data preprocessing
- **Scikit-learn** for modeling
- **Flask** for web deployment
- **HTML/CSS** for front-end

## 🙋‍♂️ Author

Made by **Mahesh Chauhan**
