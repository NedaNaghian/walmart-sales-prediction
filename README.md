# 🛒 Walmart Sales Analysis & Prediction

This project focuses on analyzing and predicting weekly sales at Walmart stores using real-world data. The goal is to explore sales patterns and build machine learning models to forecast future sales based on various economic and store-related factors.

## 📁 Dataset

The dataset includes historical sales data from Walmart, including features like:

- Store: Store number
- Date: Week of sales
- Weekly_Sales: Sales amount in USD
- Holiday_Flag: Indicates whether the week includes a public holiday
- Temperature, Fuel_Price: Environmental factors
- CPI, Unemployment: Economic indicators

Source: Public Walmart dataset (Kaggle)

## 🧠 Project Objectives

- Perform exploratory data analysis (EDA)
- Visualize trends and correlations
- Predict weekly sales using machine learning models:
  - Linear Regression
  - Random Forest Regressor

## 🧰 Tools & Libraries Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

## 📊 Key Insights

- Sales vary significantly across stores and weeks
- Public holidays influence sales behavior
- Economic indicators such as CPI and Unemployment rate show mild correlation with sales

## 🤖 Model Performance

| Model              | R² Score | Mean Squared Error (MSE) |
|-------------------|----------|---------------------------|
| Linear Regression | 0.15     | ~274,455,221,280          |
| Random Forest     | **0.93** | **~21,677,879,001**       |

✅ The Random Forest model significantly improved prediction accuracy.

## 📌 How to Use

1. Download the dataset (`Walmart.csv`)
2. Run the notebook `Walmart_Sales_Prediction.ipynb` on Google Colab or Jupyter
3. Explore the EDA and train ML models

## ✨ Author

Made with ❤️ by Neda Naghian  
Business Analytics Graduate | Passionate about Data Science & Machine Learning
