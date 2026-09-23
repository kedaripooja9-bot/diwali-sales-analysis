# 🪔 Diwali Sales Analysis

Exploratory Data Analysis (EDA) of festive-season sales data to uncover **who buys, what they buy, and where** — turning raw transaction records into actionable marketing insight.

## 📊 Overview

This project analyzes **11,251 transactions** from a Diwali sales dataset using Python to identify customer buying patterns and target demographics across gender, age, location, occupation, and product category.

## 🎯 Objective

Analyze festive-season sales data to uncover who buys, what they buy, and where — helping identify the most valuable customer segments for marketing and inventory decisions.

## 🗂️ Dataset

- **Rows:** 11,251 transactions
- **Columns:** 13 features after cleaning
- **Fields:** `User_ID`, `Cust_name`, `Product_ID`, `Gender`, `Age Group`, `Age`, `Marital_Status`, `State`, `Zone`, `Occupation`, `Product_Category`, `Orders`, `Amount`

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🧹 Data Cleaning

1. **Dropped** empty `Status` and `unnamed1` columns
2. **Cleaned** 12 rows with missing `Amount` values
3. **Typed** `Amount` cast to integer for analysis
4. **Explored** summary statistics (`describe()`) on `Age`, `Orders`, `Amount`

## 🔍 Exploratory Data Analysis

The notebook explores sales patterns across:

- **Gender** — who spends more
- **Age Group** — which generation drives the most sales
- **State** — top 10 states by orders and revenue
- **Marital Status** — spending by married vs. unmarried customers, split by gender
- **Occupation** — which professions shop the most
- **Product Category** — top-selling categories by revenue
- **Product ID** — top 10 best-selling products by order volume

## 📈 Key Findings

- **Women** drove a noticeably larger share of total sales value than men.
- The **26–35 age group** contributes the highest sales volume.
- **Uttar Pradesh, Maharashtra, and Karnataka** lead the country in sales value.
- **Married women** form the single highest-spending customer segment.
- Buyers working in **IT, Healthcare, and Aviation** post the highest sales totals.
- **Food, Clothing & Apparel, and Electronics** are the top-selling product categories.

### 🎯 Target Customer Profile

> Married women, aged 26–35, based in Uttar Pradesh, Maharashtra, or Karnataka, working in IT, Healthcare, or Aviation — most likely to buy Food, Clothing, or Electronics.


## 📁 Project Structure

```
├── Diwali Sales Data.csv          # Raw dataset
├── Diwali_Sales_Analysis1.ipynb   # Main analysis notebook
└── README.md                      # Project documentation
```
