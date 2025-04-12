# 📊 Product Performance Analysis: Optimizing Production Costs in 2024

## 📝 Introduction

### 📌 Project Description/Overview  
A company approached me to help reduce its production costs by identifying products that met specific revenue or sales targets within the first three quarters (Q1–Q3) of 2024. The objective was to determine which products were worth continuing in production and which could be phased out based on performance.

---

## 🛠️ Skills/Technologies Used

- Python  
- Pandas  
- Data Merging and Filtering  
- Datetime Manipulation  
- Exploratory Data Analysis (EDA)  

---

## ❓ Problem Statement

The company aimed to streamline production by focusing only on products that either:

- Reached a **revenue target** of **$1,500**, or  
- Achieved a **sales quantity target** of **65 units**  

Within **Q1–Q3 of 2024**.

---

## 🎯 Project Objectives

- To identify products that met the revenue or quantity thresholds.  
- To recommend profitable products for continued production.  
- To identify underperforming products that could be discontinued.  
- To determine top revenue-contributing customers.  

---

## 📦 The Data

The analysis used multiple datasets including:

- Product Information  
- Payment Records  
- Order History  
- Customer Data  

Each dataset contained essential attributes like product IDs, order dates, unit prices, payment amounts, and customer details. All date fields were converted into datetime format for accurate filtering.

---

## 🧠 Project Methodology

The project followed these analytical steps:

### 🔹 Data Collection & Preprocessing  
- Gathered and cleaned datasets related to products, payments, orders, and customers.  
- Ensured all date fields were correctly formatted for time-based filtering.  

### 🔹 Filtering for Q1–Q3 of 2024  
- Filtered order data to include only records from January to September 2024 to align with the company's timeline.  

### 🔹 Data Merging for Insights  
- Merged relevant datasets to connect product IDs with payment and order details.  
- This allowed for the calculation of total revenue per product.  

### 🔹 Identifying Profitable Products  
- Computed total units sold and revenue per product.  
- Products that met either threshold (revenue ≥ $1,500 or sales quantity ≥ 65 units) were tagged as **"profitable"**.  

### 🔹 Analyzing Customer Contributions  
- Aggregated revenue by customer to identify top contributors to overall sales.  

---

## 📈 Results

### ✅ Profitable Products  
Identified a list of products that met the company’s success criteria and were recommended for continued production.

### 💰 Cost Optimization  
Products that failed to meet either threshold were marked for potential phase-out, allowing the company to cut production costs.

### 👥 Customer Insights  
Highlighted the most valuable customers who contributed significantly to revenue, helping with customer retention strategies.

---

## 🏁 Conclusion

The analysis enabled the company to make informed decisions about which products to continue producing and which to eliminate. This focused approach supports cost reduction and resource optimization, ensuring that only high-performing products remain in the production pipeline.

---

## 🔮 Future Recommendations / Moving Forward

- **Introduce Forecasting Models:** Predict future product performance based on seasonal trends and past sales.  
- **Refine Targets Over Time:** Adjust sales/revenue targets quarterly to adapt to changing market conditions.  
- **Customer Segmentation:** Use the insights to develop targeted marketing strategies for top customer segments.

---

## 🙏 Acknowledgements

Thanks to the company for providing access to their internal data and trusting the data-driven approach to optimize production decisions.

---

> 💡 *Feel free to fork this project or reach out if you'd like to collaborate or discuss production cost optimization strategies!*
