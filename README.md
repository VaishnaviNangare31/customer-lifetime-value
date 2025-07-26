# 🧮 Customer Lifetime Value Prediction

This project focuses on predicting **Customer Lifetime Value (CLV)** using historical transaction data. Understanding CLV helps businesses identify high-value customers and tailor marketing strategies effectively.

---

## 📌 Problem Statement

Businesses often struggle to allocate marketing resources efficiently. By predicting the **lifetime value** of a customer, companies can prioritize retention efforts and make data-driven decisions.

---

## 📊 Dataset

- **Source**: [Online Retail dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- **Records**: ~500,000 transactions
- **Fields**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

---

## ⚙️ Tools & Technologies

- **Python**: Data preprocessing and modeling
- **Pandas**: Data cleaning
- **Scikit-learn**: ML models
- **Matplotlib / Seaborn**: Data visualization
- **Power BI**: Final dashboard for business insights
- **Streamlit (optional)**: Interactive web interface
- **Git/GitHub**: Version control

---

## 🧠 Approach

1. **Data Cleaning**:  
   - Removed missing `CustomerID`s  
   - Filtered cancelled transactions  

2. **Feature Engineering**:  
   - Calculated total revenue  
   - Created RFM (Recency, Frequency, Monetary) features  

3. **Modeling**:  
   - Trained regression models (e.g., XGBoost, RandomForest)  
   - Evaluated using RMSE, MAE  

4. **Power BI Dashboard**:  
   - CLV by Country  
   - Revenue Trends  
   - Top Customers  

---

## 📈 Results

- Achieved **high predictive accuracy** with XGBoost
- Identified top revenue-generating countries and customers
- Created a dashboard for non-technical stakeholders

---

## 📌 Folder Structure

