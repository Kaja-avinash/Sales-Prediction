# 🚗 Car Sales Prediction using Machine Learning

This project predicts the **car purchase amount** based on customer data using machine learning techniques. It simulates a real-world business case of forecasting sales to help companies **optimize marketing strategies** and target the right customer segments.

---

## 📊 Objective

> Forecast product sales using historical data and customer attributes such as income, gender, age, and net worth.  
> The model helps businesses identify key sales drivers and make data-driven decisions for growth.

---

## 🧠 Key Features

- Predicts car sales amounts using **Random Forest Regressor**.
- Handles **missing values**, **feature scaling**, and **categorical encoding**.
- Analyzes feature importance to highlight factors influencing purchases.
- Evaluates model with **RMSE** and **R² score**.
- Compatible with **Jupyter Notebook in VS Code**.

---

## 📁 Dataset

- **Source:** `car_purchasing.csv`
- **Features used:**
  - Gender
  - Age
  - Annual Salary
  - Credit Card Debt
  - Net Worth
- **Target:** Car Purchase Amount (Sales Value)

---

## 🔧 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook (VS Code)

---

## 📈 Workflow

1. **Data Cleaning**  
   Dropped irrelevant columns like name, email, and country.

2. **Preprocessing**  
   - Encoded categorical features.
   - Scaled numerical values using `StandardScaler`.

3. **Model Training**  
   - Used **Random Forest Regressor** for prediction.
   - Performed **train-test split** (80/20 ratio).

4. **Evaluation**  
   - Calculated **RMSE** and **R² score**.
   - Visualized **feature importance**.

5. **Model Saving**  
   - Exported trained model using `joblib`.

---

## 📂 Project Structure

Car-Sales-Prediction/ ├── notebooks/ │ └── Car_Sales_Prediction.ipynb ├── models/ │ └── car_sales_prediction_model.pkl ├── README.md ├── requirements.txt └── data/ └── car_purchasing.csv


---

## 📌 Results

| Metric      | Value             |
|-------------|-------------------|
| RMSE        | 2326.702679733135 |
| R² Score    |0.9498621195840186 |

---

## 📬 Future Improvements

- Add synthetic columns for **advertising spend** and **promotions**.
- Deploy the model using **Flask** or **Streamlit**.
- Build an interactive dashboard for sales insights.

---

