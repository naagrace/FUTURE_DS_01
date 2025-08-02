# FUTURE_DS_01
🛍️ Retail Sales Power BI Dashboard (E-commerce Analysis)
Task one of the 'Future interns Data Science and Analytics internship'

📊 Objective

To gain business insights from online retail sales data by answering key questions that help understand product performance, customer behavior, and sales trends.

## 📁 Dataset


The dataset used is publicly available on [Kaggle](https://www.kaggle.com/datasets/ertugrulesol/online-retail-data). It contains records of transactions from an online store.

## 🧹 Data Cleaning & Preparation

Data was cleaned and transformed before loading into Power BI. Key steps included:

1. Imputing missing values:
   - `Review Score`: Replaced blanks with the 'median'.
   - `Gender`: Filled missing values with the 'mode' (most frequent gender).

2. Created calculated fields in Power BI:
   - `Total Sales = Quantity * Price`
   - `Order Year` and `Order Month` were extracted from the order date for trend analysis.
   - `Average Review Score` per product/customer.

3. **Removed duplicates** and corrected **data types** (e.g., converting strings to dates or numbers where appropriate).


   ## ❓ Business Questions Answered

- What are the total sales by product category?
- Which products are selling the most in terms of quantity?
- What are the preferred payment methods among customers?
- How do sales trend over time (monthly/yearly)?
- Is there a correlation between review scores and Sales volume?
- Which cities generate the most revenue?


## 🛠️ Tools Used

- Microsoft Power BI  
- Microsoft Excel

 Power BI dashboard image<img width="1195" height="714" alt="online retail dashboard screenshot" src="https://github.com/user-attachments/assets/5721d31c-a3d2-4a63-a5b6-9085d120edbd" />

 
  
  


