# Diwali Sales Analysis (Python — Pandas, Matplotlib, Seaborn)

Exploratory Data Analysis on 11,000+ Diwali sales transactions to understand customer purchasing behavior — who buys, what they buy, and why — using Python.

![Sales by Gender](images/gender_sales.png)

## 📊 Project Overview
The raw dataset contained 11,251 order-level records (Customer info, Age, Gender, Marital Status, Occupation, State, Product Category, Orders, Amount). The goal was to clean the data and run an exploratory analysis to profile the typical Diwali-season buyer.

## 🛠️ Tools Used
- **Python** — Pandas, NumPy
- **Matplotlib & Seaborn** — data visualization
- **Jupyter Notebook**

## ❓ Business Questions Answered
- Who buys more — men or women, and who spends more?
- Which age group drives the most sales?
- Which states generate the most orders?
- Are married or single customers bigger spenders?
- Which occupations and product categories dominate sales?
- Which individual products sell the most?

## 🔑 Key Insights
- **Women account for the majority of buyers** and also have higher total purchasing power than men
- **Age group 26–35** is the biggest spending segment
- **Uttar Pradesh, Maharashtra, and Karnataka** lead in total orders and sales

![Top States by Orders](images/state_orders.png)

- **Married women** are the single biggest-spending customer segment
- Buyers working in **IT, Healthcare, and Aviation** contribute the most to sales
- **Clothing, Electronics, and Food** are the top-selling product categories

![Top Product Categories by Sales](images/category_sales.png)

## 📁 Repository Structure
```
├── Diwali_Sales_Analysis.ipynb   # Full notebook: cleaning + EDA + charts
├── Diwali_Sales_Data.csv         # Raw dataset
├── requirements.txt              # Python dependencies
├── images/                       # Chart exports used in this README
└── README.md
```

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook Diwali_Sales_Analysis.ipynb
```

## 📌 Conclusion
Married women aged 26–35 from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation, are the most likely to purchase Food, Clothing, and Electronics — a segment worth prioritizing in future campaigns.
