# 🏡 House Price Prediction using Linear Regression

This project focuses on building a basic machine learning model to predict house prices using **Linear Regression**. The dataset used is a simplified version of the **Ames Housing Dataset**, containing various features of residential properties.

---

## 📌 Project Overview

In this project, I explored how housing features influence the final sale price and built a regression model to predict house prices.

## 📁 Dataset
The dataset used in this project is [Ames Housing Data](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).  
Make sure the file `train.csv` is available in the project directory.

---

## ✅ Tasks Performed

### 🔹 Imported essential Python libraries
Used **pandas**, **NumPy**, **Matplotlib**, **Seaborn**, and **scikit-learn** for data processing, visualization, and model building.

### 🔹 Loaded the dataset
Worked with the `train.csv` file containing **81 columns** of data on real estate properties.

### 🔹 Selected relevant features
Focused on four major features for prediction:
- Above ground living area (`GrLivArea`)
- Number of bedrooms above ground (`BedroomAbvGr`)
- Number of full bathrooms (`FullBath`)
- Number of half bathrooms (`HalfBath`)

### 🔹 Handled missing data
Ensured the dataset was clean by dropping rows with missing values in selected columns.

### 🔹 Split the data
Divided the dataset into **80% training** and **20% testing** sets to evaluate model performance fairly.

### 🔹 Trained a Linear Regression model
Built a **Linear Regression** model using the selected features to predict house sale prices.

### 🔹 Made predictions and evaluated performance
Predicted house prices on the test set and evaluated the model using:
- 📉 **Mean Squared Error (MSE)**
- 📈 **R² Score (coefficient of determination)**

Achieved an **R² Score of 0.63**, showing a moderate correlation between the selected features and the target variable.

### 🔹 Visualized results
Plotted a **scatter plot** comparing **actual vs. predicted** house prices to visualize model accuracy and identify prediction trends.

---

## 📈 Outcome

The model provides a **decent baseline** for house price prediction using only four features. With further feature engineering and advanced models, the accuracy can be significantly improved.

---

## 📚 Learnings

- Importance of **feature selection** and **data cleaning**
- Basics of **Linear Regression** and its assumptions
- Model evaluation using metrics like **MSE** and **R² Score**
- **Visualization** of prediction accuracy

---

## 🚀 Future Scope

- Use more features from the dataset for better prediction
- Apply **feature scaling** and **encoding**
- Experiment with **polynomial regression** or **ensemble models** (e.g., Random Forest, XGBoost)
- Perform **cross-validation** for robust model evaluation

---

