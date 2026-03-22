# Amazon (AMZN) Stock Price Forecasting 📈

A comprehensive Machine Learning pipeline to predict Amazon's daily closing prices. This project compares industry-standard models with a custom mathematical implementation to validate predictive accuracy.

## 🚀 Key Features
* **Custom ML from Scratch:** Manual implementation of Multivariate Linear Regression using Gradient Descent (no library abstractions).
* **Multi-Model Comparison:** Evaluation of SVR (Linear), Random Forest, and XGBoost.
* **Feature Engineering:** Integration of 100+ features including RSI, MACD, Bollinger Bands, and multi-day lags from major tech stocks (AAPL, MSFT, GOOGL).
* **Robust Evaluation:** Performance metrics based on MAE, RMSE, and R² Score.

## 📊 Final Results (SVR)
The **Support Vector Regressor** was the top-performing model:
* **MAE:** $3.81 USD
* **MAPE:** 1.67%
* **R² Score:** 0.8373

## 🛠️ Tech Stack
* **Language:** Python 3.9+
* **Libraries:** Scikit-Learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn.
* **Tools:** Jupyter Notebook, VS Code.

## 📁 Project Structure
* `prediccion_acciones.ipynb`: Main notebook with full pipeline and visualizations.
* `data/`: (Optional) Folder for raw datasets.
* `outputs/`: Generated plots and performance tables.

---
**Developed by Gabriel RODRIGUEZ POSTIGO**
*Computer Science Student @ UCSP*
*Arequipa, Perú*
