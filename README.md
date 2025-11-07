# 🛒 E-Commerce Sales Analysis using Python

**Author:** Veer Pratap  
**Tools:** Python • Pandas • Matplotlib • Seaborn • Numpy  

---

## 🎯 Project Objective
The goal of this project is to **analyze and visualize E-commerce sales data** to derive business insights such as:
- Revenue and Profit performance
- Sales trend over time
- Top-performing categories, regions, and customers
- Profitability and discount analysis

---

## ⚙️ Project Workflow
### 🔹 Step 1: Data Loading  
Data imported directly from a GitHub-hosted CSV file using pandas.

### 🔹 Step 2: Data Cleaning & Transformation  
- Removed missing values  
- Converted date columns to `datetime` format  
- Created new fields like `Profit Margin (%)`, `Month`, and `Year`

### 🔹 Step 3: Exploratory Data Analysis (EDA)  
- Descriptive statistics  
- Category-wise, region-wise, and customer-level breakdown  
- Correlation analysis among numerical features  

### 🔹 Step 4: Visualization & Insights  
Generated multiple visualizations:
1. Monthly Sales Trend  
2. Category-wise Sales  
3. Region-wise Profit  
4. Top 10 Customers by Sales  
5. Profit by Sub-Category  
6. Correlation Heatmap  

---

## 📊 Key Insights
- **Technology** and **Office Supplies** dominate sales.  
- **West Region** shows the highest profit share.  
- **December** experiences peak monthly sales.  
- Profit margin averages around **12–15%**, showing healthy business growth.  
- Heavy discounts correlate negatively with profit (visible in heatmap).

---

## 🖥️ How to Run
````
pip install pandas numpy matplotlib seaborn
python ecommerce_sales_analysis.py
