# 🛒 Big Mart Sales Prediction

> An end-to-end regression machine learning project that forecasts item-level sales across a supermarket chain — turning historical transaction data into store-level revenue predictions decision-makers can actually plan against.

---

## 📌 Problem Statement

A large supermarket company operates several stores around the world and wants to know, in advance, how much each product is likely to sell at each outlet.

Sales forecasting isn't just a number on a dashboard — it drives real business decisions. This project builds a regression model that takes historical item and outlet data and predicts future sales, so the business can plan inventory, staffing, and strategy around a data-backed estimate instead of a guess.

---

## 🎯 Business Applications

What does an accurate sales forecast actually unlock? Five concrete outcomes:

| Outcome | Why It Matters |
|---|---|
| 💰 **Predict Sales Revenue** | Ground revenue expectations in data instead of intuition, per store and per product |
| 🔍 **Perceive Challenges Early** | Spot underperforming stores or SKUs before the quarter closes, not after |
| 📈 **Aid Future Marketing Plans** | Direct promo spend toward products and outlets where lift will be highest |
| 👥 **Plan Recruitment Strategy** | Size store staffing to forecasted demand instead of last year's headcount |
| 🎯 **Motivate Sales Teams** | Set targets that are grounded in realistic, model-backed numbers |

---

## 🔄 Work Flow

The project follows a standard supervised ML pipeline, end to end:

| Stage | What Happens |
|---|---|
| 🗂️ **Data** | Load the Big Mart sales dataset (item attributes, outlet attributes, historical sales) |
| ⚙️ **Data Pre-processing** | Handle missing values, encode categorical variables, standardize formats |
| 🔎 **Data Analysis** | Explore distributions, correlations, and relationships between features and sales |
| ✂️ **Train-Test Split** | Partition the data to train the model on one slice and evaluate on unseen data |
| 🌳 **XGBoost Regressor** | Train a gradient-boosted decision tree model to predict `Item_Outlet_Sales` |
| 📋 **Evaluation** | Measure model accuracy on the test set (R², MAE, RMSE) |

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/-XGBoost-337AB7?style=flat&logo=xgboost&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 📊 Model Choice: Why XGBoost?

XGBoost (Extreme Gradient Boosting) is a strong default for structured/tabular regression problems like this one — it handles mixed feature types, is robust to missing values, and consistently ranks near the top on retail forecasting benchmarks.

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/aarpai/big-mart-sales-prediction.git
cd big-mart-sales-prediction

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook Big_Mart_Sales_Prediction.ipynb
```

---
