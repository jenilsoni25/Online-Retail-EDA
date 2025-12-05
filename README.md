# 🛍️ Online Retail Exploratory Data Analysis (EDA)

This project performs a complete Exploratory Data Analysis (EDA) on the popular **UCI Online Retail Dataset**, which contains transactional data for a UK-based online store.  
The goal is to uncover business insights related to **sales trends, product performance, customer behavior, and returns**.

---

## 📌 Project Objectives
The analysis aims to:

- Understand the structure and quality of the dataset  
- Explore sales patterns across time, products, and countries  
- Identify top products and top revenue-generating markets  
- Analyze returns and detect abnormal patterns  
- Perform **RFM customer segmentation**  
- Conduct statistical hypothesis testing  
- Provide actionable business recommendations  

---

## 📊 Key Analysis Performed

### **1. Data Cleaning**
- Standardized column names  
- Parsed dates correctly  
- Removed cancellation invoices  
- Handled missing `CustomerID`  
- Separated **sales** and **returns**  
- Created new features:
  - `total_price`
  - `year`, `month`, `day`, `hour`

---

### **2. Sales Insights**
- Monthly revenue trend and seasonality  
- Revenue by country  
- Hourly and daily purchasing behavior  
- Identification of top-performing products  

---

### **3. Product Insights**
- Top products by revenue  
- Top products by quantity  
- High return-rate products (potential defects, shipping issues)

---

### **4. Customer Analysis (RFM Segmentation)**
Each customer was assigned:

- **Recency**
- **Frequency**
- **Monetary value**

Segments identified:

- 🏆 **VIP Customers**  
- 💙 **Loyal Customers**  
- ⚠️ **At Risk**  
- 🚀 **New Customers**  
- ❌ **Lost Customers**  
- ⭐ **High-Value At Risk**

---

### **5. Hypothesis Testing**
Used **Mann-Whitney U test** to validate:

#### 📌 Hypothesis 1  
**Holiday months (Nov–Dec) have higher revenue?**  
➡ Result: *Not statistically significant*

#### 📌 Hypothesis 2  
**UK has higher average order value than other countries?**  
➡ Result: *Not statistically significant*

---

### **6. Data Issues Identified**
- Missing customer IDs  
- Negative quantities (returns)  
- Non-product stock codes (`POST`, `DOT`)  
- Extreme return rates on some SKUs  
- Outliers in price and quantity  

---

## 🧠 Business Recommendations

- Target **VIP and loyal customers** with retention campaigns  
- Investigate **high-return SKUs** for quality/supply-chain issues  
- Improve **customer data capture** processes  
- Promote **top-performing products** using targeted marketing  
- Expand focus beyond the UK to diversify revenue  
- Monitor SKU-level performance more closely to reduce returns  

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SciPy**
- **Jupyter Notebook**
- 
✨ Author

Jenil — Data Science Enthusiast
Feel free to connect or open issues on GitHub!

