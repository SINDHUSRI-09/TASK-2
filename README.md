# TASK-2
Global supersales  using power BI
Absolutely! Here's a clean and professional `README.md` for your **Global Superstore Dashboard**, formatted just like your Task 1 submission:

---

# 📊 Task 2: Power BI Dashboard – Global Superstore

### 💼 Internship Role: Data Analyst

This task involved cleaning a global retail dataset and creating an interactive dashboard using **Power BI** to uncover sales and profit insights across various dimensions.

---

## 📁 Dataset Used

**File Name**: `Global Superstore Dataset`\
(A transactional dataset with sales, profit, product, customer, and regional information.)

---

## 🧹 Data Cleaning & Preparation

### 1️⃣ Missing Values

- Identified and removed rows with missing values in key fields such as:
  - `Sales`, `Profit`, `Category`, `Region`, `Customer Name`
- For some non-critical fields (like `Postal Code`), missing values were left as-is or marked as `N/A`.

### 2️⃣ Error Correction & Formatting

- Corrected **spelling errors** in categorical fields:
  - e.g., `"Offc Supplies"` → `"Office Supplies"`
- Ensured consistency in values across:
  - `Ship Mode`, `Segment`, `Region`, `Product Category`

### 3️⃣ Column Formatting

- Reformatted:
  - `Order Date` and `Ship Date` columns to **dd-mm-yyyy**
  - Numeric fields like `Sales`, `Quantity`, and `Profit` to appropriate **decimal formats**

### 4️⃣ Data Type Checks

- Verified and adjusted data types:
  - **Text**: Customer, Product, Region
  - **Number**: Quantity, Sales, Profit
  - **Date**: Order Date, Ship Date

### 5️⃣ Duplicates

- Removed duplicate transactions based on `Order ID` and `Product ID`.

---

## 📊 Dashboard Overview

An interactive Power BI dashboard was created to visualize the cleaned dataset with the following insights:

### 🎯 Filters

- **Country**, **State**, and **City** slicers
- **Region Buttons**: Central, East, South, and West

### 📈 Visuals Included

- **Sales by Payment Mode** – Bar chart
- **Sales by Region** – Donut chart
- **Sales by Segment** – Column chart
- **Sales by Sub-Category** – Bar chart
- **Sales by Ship Mode** – Bar chart
- **Sales by Category** – Column chart
- **Profit & Quantity by Sub-Category** – Combo (bar + line) chart

---

## 💡 Insights Uncovered

- **South** region leads in total sales.
- **Standard Class** is the most preferred shipping method.
- **Office Supplies** is the top-selling product category.
- **Chairs**, **Phones**, and **Binders** are the best-performing sub-categories in terms of profit and quantity sold.

---

## 🛠 Tools Used

- ✅ Power BI Desktop
- ✅ Power Query Editor (for data transformation)
- ✅ Microsoft Excel (for initial data inspection)

---

Let me know if you want a version that includes a downloadable `.pbix` file section or instructions on how to connect the data!
