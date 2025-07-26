# 🛒 E-commerce Sales Analysis

A comprehensive data analysis project using a UK-based online retail dataset to extract meaningful business insights through exploratory data analysis (EDA), KPI evaluation, and customer segmentation using RFM analysis.

---

## 📌 Project Overview

This project focuses on analyzing online retail transactions between **December 2010 to December 2011** from a UK-based store. The dataset includes invoice numbers, product descriptions, quantities, customer IDs, and countries.

---

## 📂 Dataset Details

- **Source**: `data/online_retail.csv`
- **Rows**: 541,909
- **Columns**: 8
- **Attributes**:
  - `InvoiceNo`: Invoice number (can start with 'C' for canceled orders)
  - `StockCode`: Product/item code
  - `Description`: Product name
  - `Quantity`: Number of items per transaction
  - `InvoiceDate`: Date and time of purchase
  - `UnitPrice`: Price per item (in pounds)
  - `CustomerID`: Unique customer identifier
  - `Country`: Country of the buyer

---

## 🧪 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧹 Data Cleaning

- Removed rows with null values in `CustomerID`
- Filtered out canceled transactions (`InvoiceNo` starting with 'C')
- Removed entries with negative or zero quantity and unit price

---

## 📊 Exploratory Data Analysis (EDA)

Key insights discovered:
- 📈 **Top Selling Products**
- 🗓️ **Monthly Sales Trends**
- 🌍 **Sales by Country**
- 👤 **Most Valuable Customers**
- 💸 **Revenue per Month**

---

## 📦 RFM Customer Segmentation

Implemented **RFM (Recency, Frequency, Monetary)** analysis to identify:
- 🟢 Loyal customers
- 🟡 Frequent buyers
- 🔴 At-risk and churned customers

---

## 📁 Project Structure

