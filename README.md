# 🚗 Used Car Price Prediction

A machine learning project that predicts the resale price of used cars using various regression models and real-world data features like year, mileage, fuel type, engine specs, etc.

---

## 📊 Model Performance

| Model                  | R² Score (Test) | MAE (₹)      | RMSE (₹)     |
|------------------------|----------------|--------------|--------------|
| Linear Regression      | 0.6645         | 279,619      | 502,544      |
| Lasso                  | 0.6645         | 279,615      | 502,543      |
| Ridge                  | 0.6645         | 279,557      | 502,534      |
| K-Neighbors Regressor  | 0.9150 ✅      | 112,526      | 253,024      |
| Decision Tree          | 0.8812         | 123,967      | 299,094      |
| **Random Forest**      | **0.9334** ⭐   | **101,419**  | **223,925**  |
| Adaboost Regressor     | 0.6639         | 337,110      | 502,986      |

> ✅ **Best model**: **Random Forest Regressor** with **R² = 0.9334**, **MAE ≈ ₹1.01 Lakh**, and **RMSE ≈ ₹2.24 Lakh**.

---

    ## 📁 Project Structure

    Used-Car-Price-Prediction/
    │
    ├── notebooks/
    │ └── main.ipynb
    │
    │
    ├── requirements.txt
    ├── README.md
    └── .gitignore

yaml
Copy
Edit

---


🧠 ML Techniques Used
- Data Preprocessing: Handling missing values, encoding categorical variables, scaling.

- Exploratory Data Analysis (EDA): Insights using seaborn, plotly.

- Model Selection: Linear, Lasso, Ridge, KNN, Decision Tree, Random Forest, Adaboost.

- Performance Metrics: MAE, RMSE, R² score.

- Cross-validation and test evaluation.

🛠️ Tech Stack
- Python 🐍

- Pandas, NumPy, Scikit-learn

- Matplotlib, Seaborn, Plotly

- Jupyter Notebook




