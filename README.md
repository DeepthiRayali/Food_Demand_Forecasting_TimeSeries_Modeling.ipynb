🥗 Food Supply Chain Demand Forecasting (Time Series Analysis)
📘 Overview

This project focuses on time series forecasting and modeling of food demand in a supply chain using various machine learning and deep learning algorithms.
Accurate demand forecasting is critical in the food industry to minimize waste and avoid shortages, especially for perishable products.

🎯 Objective

To build and evaluate forecasting models that predict food demand over a 10-week horizon by leveraging lag features and regressor-based analysis.

📊 Dataset

Source: GENPACT Food Supply Dataset (available on Kaggle
)

Contains weekly sales data for multiple meal centers, regions, and product categories.

Target variable: Orders (Sales)

Lag data and exponentially weighted moving average (EWMA) used for feature engineering.

⚙️ Methodology

Data exploration and visualization

Feature engineering (lag features, EWMA, mean/max/min statistics)

Data normalization and train-test split

Model training using:

Random Forest

Gradient Boosting

XGBoost

CatBoost

LightGBM

LSTM

Bi-LSTM

CNN2D (extension model)

Evaluation using RMSE, MAE, MAPE, and RMSLE

🧠 Key Results

LSTM achieved the lowest MAE and RMSE among baseline models.

CNN2D (extension model) further improved accuracy with MAE ≈ 9.

📈 Visualization

Multiple plots demonstrate sales trends, regional demand distribution, and correlation heatmaps for better insight into influencing factors.

💻 Tools & Libraries

Python, Jupyter Notebook

Pandas, NumPy, Scikit-learn

Matplotlib, Seaborn

XGBoost, LightGBM, CatBoost

TensorFlow / Keras (for LSTM, CNN2D)

🏁 Conclusion

The project demonstrates how combining time series features with deep learning models significantly improves the accuracy of demand forecasting in the food supply chain.# Food_Demand_Forecasting_TimeSeries_Modeling.ipynb
The project demonstrates how combining time series features with deep learning models significantly improves the accuracy of demand forecasting in the food supply chain.
