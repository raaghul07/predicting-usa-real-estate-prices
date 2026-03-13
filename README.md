# 🏠 USA Real Estate Price Analysis & Prediction

Exploratory data analysis and machine learning model to predict US property prices using 91,000+ real estate listings.

## 📊 Project Overview
This project analyzes a large US real estate dataset to uncover what drives property prices and builds a Random Forest regression model to predict them.

## 📁 Dataset
- **Source:** [USA Real Estate Dataset - Kaggle](https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset)
- **Size:** 115,371 listings across the US (91,063 after cleaning)
- **Features:** bed, bath, house_size, acre_lot, city, state, zip_code, price

## 🔍 Key Findings
- Bath count and house size are the strongest predictors of price
- Massachusetts has the highest median property price (~$600k)
- Acre lot size has minimal impact on price
- Bed and bath counts are highly correlated (0.72)

## 🤖 Model Performance
| Metric | Score |
|--------|-------|
| R² Score | 0.494 |
| RMSE | $381,806 |
| Algorithm | Random Forest Regressor |

## 🛠️ Tech Stack
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📓 Notebook
See `USA_Real_Estate_Price_Analysis_and_Prediction.ipynb` for the full analysis.
