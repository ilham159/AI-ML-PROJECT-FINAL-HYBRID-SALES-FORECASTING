📊 Explainable Hybrid SARIMA–LightGBM Model
Multi-Horizon E-Commerce Sales Forecasting
📌 Project Overview

This project was developed as part of a Portfolio Presentation session (Day 57) to demonstrate end-to-end machine learning capability — from business problem identification, data preprocessing, modeling, evaluation, to business insight generation.

The objective of this project is to build an explainable multi-horizon sales forecasting model using a hybrid SARIMA–LightGBM approach to support data-driven business decision-making in e-commerce.

🎯 Business Problem

E-commerce companies need accurate sales forecasting to:

Optimize inventory planning

Improve supply chain efficiency

Reduce stock-out and overstock risk

Support financial and operational decision-making

Traditional statistical models capture seasonality well, while machine learning models capture nonlinear patterns. This project combines both approaches.

📂 Dataset

Dataset used:

Global E-Commerce Dataset (1M+ Records, 2024–2026)

Includes transaction-level information such as:

Order date

Product category

Payment value

Customer behavior

Profit margin

Order priority

⚙️ Project Workflow

Data Understanding & Cleaning

Exploratory Data Analysis (EDA)

Feature Engineering (time-based features, trend components)

Time-Series Splitting (Train/Test & Cross Validation)

Model Development:

SARIMA (statistical baseline)

LightGBM (machine learning model)

Hybrid SARIMA–LightGBM

Model Evaluation using:

MAE

RMSE

Visualization & Business Insight

🤖 Models Used
1️⃣ SARIMA

Used to capture seasonality and trend patterns in time-series data.

2️⃣ LightGBM

Used to model nonlinear relationships and complex feature interactions.

3️⃣ Hybrid Model

Residual from SARIMA is modeled using LightGBM to improve prediction accuracy.

📈 Results

The hybrid model shows improved forecasting performance compared to standalone SARIMA.

Key improvements:

Better handling of peak seasonal demand

Lower RMSE compared to baseline

More stable multi-horizon prediction

💡 Business Insights

Sales show strong seasonal peaks during Q4

High-margin products significantly impact revenue trend

Multi-horizon forecasting enables better stock allocation planning

Hybrid modeling improves decision reliability

🔮 Future Improvements

Incorporate external variables (holiday effects, marketing campaign data)

Deploy as interactive dashboard (Tableau / Streamlit)

Apply explainability techniques (SHAP values)

👨‍💻 Author

Ilham Dyki Mu'ahfi
Master of Information Technology
Data Analytics & Machine Learning Enthusiast
