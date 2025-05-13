# 🚗 Price Prediction for Used Cars

This project uses supervised machine learning to predict the selling price of a used car based on various features such as mileage, power, engine size, number of seats, and more. The solution is designed to assist car buyers, sellers, and dealerships in making data-driven pricing decisions.

---

## 📌 Problem Statement

Used car prices are influenced by several factors such as age, brand, mileage, engine power, and more. The goal of this project is to develop a regression model that accurately predicts the price of a used car using historical sales data and car specifications.

---

## 🧠 Solution Approach

A machine learning pipeline was implemented that includes:

- Data cleaning and preprocessing
- Feature engineering and encoding
- Exploratory data analysis (EDA)
- Model training with various regression algorithms
- Performance evaluation using standard metrics

---

## 🔍 Key Observations

- 📍 **Location** of the car plays a significant role in price prediction.
- ⏳ Older cars tend to depreciate in value — **years used** negatively correlates with price.
- 🛣️ **Mileage** and **kilometers driven** affect the value but with diminishing returns.
- ⚙️ Higher **engine capacity**, **power**, and **number of seats** contribute positively to price.
  
These insights provide valuable cues for dynamic pricing strategies in the used car market.

---

## 📊 Dataset Overview

The dataset includes the following features:

| Feature           | Description                             |
|-------------------|-----------------------------------------|
| `year`            | Year of manufacture                     |
| `location`        | Selling location                        |
| `kilometers_driven` | Total distance the car has been driven |
| `fuel_type`       | Type of fuel used                       |
| `transmission`    | Manual or Automatic                     |
| `owner_type`      | First, Second, Third, etc.              |
| `mileage`         | Mileage of the car                      |
| `engine`          | Engine capacity                         |
| `power`           | Power of the vehicle                    |
| `seats`           | Number of seats                         |
| `price`           | Target variable                         |

---

## ⚙️ Tech Stack

- **Python 3.x**
- **Jupyter Notebook**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – ML models and preprocessing
- **XGBoost** – Advanced gradient boosting

---

## 📈 Model Evaluation

The following regression models were evaluated:

- **Linear Regression**
- **Ridge & Lasso Regression**
- **Random Forest Regressor**
- **XGBoost Regressor**

**Evaluation Metrics:**

| Metric     | Description                          |
|------------|--------------------------------------|
| R² Score   | Proportion of variance explained     |
| RMSE       | Root Mean Squared Error              |
| MAE        | Mean Absolute Error                  |

> 📌 *XGBoost produced the best performance with the highest R² and lowest RMSE.*

---

## 🛠️ How to Use

### 1. Clone the Repository

bash
git clone https://github.com/mkador/used-car-price-prediction.git
cd used-car-price-prediction

---

## 2. Set Up the Environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt


## 3. Run the Notebook
jupyter notebook

Open the used_car_price_prediction.ipynb notebook and run all cells.

---

## 📦 Folder Structure
used-car-price-prediction/
│
├── used_car_price_prediction.ipynb   # Main project notebook
├── data/                             # (Optional) Raw or cleaned data files
├── models/                           # (Optional) Saved models
├── requirements.txt                  # Python dependencies
└── README.md                         # Project documentation
---
## 🚀 Future Work
Model deployment using Flask or Streamlit

API for real-time car price predictions

Integration with online car resale platforms

Incorporate images or textual descriptions using deep learning


---
## 👨‍💻 Author
Md. Musa kalimulla
Data Scientist & ML Engineer
GitHub • LinkedIn

