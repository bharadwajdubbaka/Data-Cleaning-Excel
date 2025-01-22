# 📊 Data Cleaning and Combining Data in Excel – Project 1

![Excel Banner](https://user-images.githubusercontent.com/your-image-url/banner.png)

---

## 🚀 Overview

This project focuses on transforming raw data into actionable insights by performing **data cleaning** and **data merging** operations using Microsoft Excel. The objective is to enhance data quality for better analysis and decision-making.

📄 **Presentation File:** [Download the PPT](./Data_Cleaning_Excel_Project.pptx)

---

## 📂 Project Scope

The project involves three key datasets:

1. **Orders Table**  
   - Order details such as Order ID, Customer ID, Product ID, Date, and Quantity.

2. **Products Table**  
   - Product details including Product ID, Name, Nutritional Values, and Price.

3. **Customer Table**  
   - Customer names and their corresponding Customer IDs.

### 🎯 Objectives

- ✅ Clean and transform raw data to ensure accuracy and consistency.
- ✅ Use Excel formulas to merge datasets for analysis.
- ✅ Prepare data for reporting and visualization.

---

## 🛠️ Data Cleaning Process

### 1️⃣ Orders Table

- 🔹 **Removed duplicate `order_id`** to prevent data redundancy.
- 🔹 **Converted `product_id` to text** format for consistency.
- 🔹 **Corrected `qty` entries** by removing trailing "Q" characters.
- 🔹 **Replaced empty values** in `qty` column with "Not Available."

### 2️⃣ Products Table

- 🔹 Applied `TRIM()` to remove extra spaces in `product_name.`
- 🔹 Extracted numerical values from the `price (in Rs)` column.
- 🔹 Renamed columns for clarity.

### 3️⃣ Customer Table

- 🔹 Converted customer names to lowercase using `PROPER()` function.
- 🔹 Used "Paste Special" to store cleaned values permanently.

---

## 🔄 Data Merging Process

After data cleaning, the following Excel functions were used to merge tables and gain insights:

| Function       | Purpose                                   |
|----------------|-------------------------------------------|
| **VLOOKUP()**   | Retrieve customer names using `customer_id` |
| **INDEX-MATCH()** | Fetch product names using `product_id`     |
| **XLOOKUP()**   | Obtain product prices from product IDs      |
| **Formula**     | Calculate total price as `qty * price`      |

---

## 📊 Final Cleaned and Combined Dataset

The final dataset includes:

- Order details enriched with customer names and product information.
- Clean and structured data ready for reporting and business insights.

---

## 💡 Key Learnings

Through this project, I gained hands-on experience in:

- 🔸 Handling duplicates and data consistency issues.
- 🔸 Applying Excel formulas like `VLOOKUP`, `INDEX-MATCH`, and `XLOOKUP`.
- 🔸 Cleaning and preparing datasets for further analysis.

---

## 📁 Explore My Work

🔗 **LinkedIn:** [Your LinkedIn Profile](https://linkedin.com/in/your-profile)

---

**📩 Feel free to explore my work and provide feedback!**

---

