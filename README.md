# 🛒 Supermart Grocery Sales – Retail Analytics & Machine Learning

A data analytics and machine learning project focused on understanding retail sales performance and predicting supermarket sales using historical transaction data.

---

## 📌 Project Overview

This project analyzes grocery sales data from a supermarket to uncover business insights and build predictive models for sales forecasting. The dataset includes transaction-level details such as product categories, customer locations, discounts, and profit.

The objective is to support **data-driven retail decisions** through analytics and machine learning.

---

## 🎯 Business Objectives

- Analyze **sales and profit trends**
- Identify **high-performing products and regions**
- Understand the **impact of discounts on profitability**
- Detect **seasonal patterns in sales**
- Build machine learning models to **predict future sales**

---

## 🗂 Dataset Description

Each record represents a single customer order and includes:

| Category | Columns |
|----------|---------|
| Order Info | Order ID, Order Date |
| Customer Info | Customer Name |
| Product Info | Category, Sub Category |
| Location Info | City, Region, State |
| Financial Info | Sales, Discount, Profit |

---

## 🧹 Data Preprocessing

The following steps were performed:

- Removed missing and duplicate records  
- Converted `Order Date` into datetime format  
- Extracted new features: `Order Day`, `Order Month`, `Order Year`, `Month Name`  
- Encoded categorical variables using Label Encoding  
- Scaled features for machine learning models  

---

## 📊 Exploratory Data Analysis

Key analyses performed:

- 📦 **Sales by Category**
- 💰 **Profit by Category**
- 💸 **Discount vs Profit**
- 📈 **Monthly Sales Trend**
- 🌍 **Region-wise Sales**
- 🏙 **Top Cities by Sales**
- 🔥 **Correlation Heatmap**

---

## 🤖 Machine Learning Models

Three regression models were trained to predict **Sales**:

| Model | Description |
|------|-------------|
| Linear Regression | Baseline model assuming linear relationships |
| Random Forest Regressor | Ensemble model capturing nonlinear patterns |
| Gradient Boosting Regressor | Boosting model for improved prediction accuracy |

### 📏 Evaluation Metrics

- **RMSE (Root Mean Squared Error)**  
- **R² Score**

After comparison, **Linear Regression** performed slightly better, indicating that the available features have mostly linear relationships with sales.

---

## 📉 Model Performance Visualization

- Actual vs Predicted Sales plot  
- Residual error analysis  

These plots show that while the model captures general trends, sales variability is influenced by additional external factors not present in the dataset.

---

## 🧠 Key Insights

- Some product categories generate high sales but low profit due to heavy discounting  
- Higher discounts generally reduce profit margins  
- Certain cities and regions contribute significantly to overall revenue  
- Sales show seasonal patterns across months  
- Sales prediction accuracy can improve with additional business features like promotions or holidays  

---

## 🚀 Future Improvements

- Add more business features (festivals, promotions, customer segments)  
- Use advanced feature engineering  
- Hyperparameter tuning for ensemble models  
- Deploy the model into a dashboard for real-time predictions  

---

## 🛠 Tech Stack

- **Python**
- **Pandas, NumPy** – Data processing  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-learn** – Machine learning  

---

## ⚙️ How to Run This Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/vishalrox/Supermart_grocery_sales_analysis.git
cd Supermart_grocery_sales_analysis
```

## Install Dependencies
```
pip install -r requirements.txt
```

## Run the Notebook

jupyter notebook


## 📁 Project Structure
```bash
📦 Supermart-Sales-Analytics
 ┣ 📜 Supermart_sales_analysis.ipynb
 ┣ 📜 supermart_grocery_sales.csv
 ┣ 📜 requirements.txt
 ┗ 📜 README.md
```

## 📬 Author

Vishal Mehta
Focused on applying analytics and machine learning to solve real-world business problems.


---

⭐ If you found this project helpful, feel free to star the repository!


