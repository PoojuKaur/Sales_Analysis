# Sales_Analysis

# 🪔 Diwali Sales Data Analysis (Python Project)

## 📌 Project Overview

This project analyzes Diwali sales data using Python to understand customer behavior, purchasing patterns, and key business insights. The goal is to identify which customers contribute the most to sales and what products perform best.

---

## 🛠️ Tools & Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn

---

## 📂 Dataset Information

The dataset contains **11,251 rows and 15 columns**, including:

* Customer details (User_ID, Gender, Age, Marital Status)
* Location (State, Zone)
* Occupation
* Product details (Category, Product ID)
* Sales data (Orders, Amount)

---

## 🧹 Data Cleaning Steps

* Removed empty columns (`Status`, `unnamed1`)
* Checked for missing values
* Dropped rows with null values in `Amount`
* Converted `Amount` column to integer type
* Renamed column `Marital_Status` to `Shaadi`

---

## 📊 Exploratory Data Analysis (EDA)

### 👩‍🦰 Gender Insights

* Most buyers are **female**
* Females also have **higher total spending** than males

---

### 🎂 Age Group Insights

* Highest number of buyers are aged **26–35 years**
* This group contributes the **most to total sales**

---

### 🌍 State-wise Sales

Top states by orders and revenue:

* Uttar Pradesh
* Maharashtra
* Karnataka

---

### 💍 Marital Status

* **Married women** are the biggest buyers
* They also show the **highest purchasing power**

---

### 💼 Occupation

Top contributing occupations:

* IT sector
* Healthcare
* Aviation

---

### 🛍️ Product Categories

Most popular categories:

* Food
* Clothing
* Electronics

---

### 🏆 Top Products

* Identified top 10 most sold products based on number of orders

---

## ✅ Conclusion

The analysis shows that:

> **Married women aged 26–35 from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation, are the most valuable customers.**
> They are most likely to purchase products from **Food, Clothing, and Electronics categories.**

---


## 📎 How to Run

1. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Run the Jupyter Notebook or Python script
3. Make sure the dataset file is in the same directory

---

## ⭐ Author

**Poojinder Kaur**
BSc Computer Science Student | Aspiring Data Analyst

---

