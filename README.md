# **AtliQ Hardware Sales Analysis Project**

## **Problem Statement**  
AtliQ Hardware, a company specializing in delivering computer hardware and peripherals to manufacturers, operates multiple branches across India. The sales director has been struggling to assess business performance due to declining sales. Whenever he reaches out to regional managers for updates, he encounters challenges—many managers find it difficult to interpret raw numerical data from Excel files. This lack of clarity contributes to frustration and hinders effective decision-making.  

## **Solution**  
To address this, the sales director decided to implement a **Power BI dashboard** for **data-driven decision-making** through visual representation. A team of data professionals was hired to carry out this project.  

## **Project Planning with AIMS Grid**  
Using the **AIMS Grid** project management tool, the team established the project's **purpose, key stakeholders, desired outcomes, and success criteria** to ensure a structured approach.  

## **Steps Followed in This Project**  
1. **Project Planning** – Learned about the AIMS Grid methodology.  
2. **Data Retrieval** – Used **MySQL** to extract data from the company’s database into **Power BI**.  
3. **Data Cleaning** – Processed and refined the data using **Power Query**.  
4. **ETL Process** – Extracted, transformed, and loaded the data for analysis.  
5. **Measure Creation** – Developed DAX measures for business insights and applied them in Power BI.  
6. **Currency Conversion** – Standardized transaction values by converting different currency types.  
7. **Data Validation** – Ensured data accuracy before visualization.  
8. **Data Modeling & Visualization** – Structured the data and created interactive reports.  

## **Major Customizations & Improvements**  
- **Resolved the '(blank)' issue** in the products section by replacing the original products table with a **self-modified** version containing product data (Prod280 to Prod339) with assigned types (either ‘Own Brand’ or ‘Distribution’).  
- **Merged the original and modified** `sales_transaction` tables to include key financial metrics such as **profit margin, cost price, etc.**  

## **Key Insights from the Dashboard**  

### **Overall Performance (4 Years)**  
- **Total Revenue:** ₹985M  
- **Total Profit Margin:** ₹24.7M (2.5%)  
- **Total Sales Quantity:** 2M units  

### **Yearly Insights (2020)**  
- **Revenue:** ₹142M  
- **Total Units Sold:** 350K  
- **Profit:** ₹2.1M  

### **Top Market Performers**  
- **Delhi NCR:** Largest market by revenue (₹520M, 52.8% share) but low profit margin (2.3%).  
- **Bhubaneswar (2020):** Highest profit margin (10.48%).  
- **Mumbai:** Largest contributor to total profit (23.89%).  
- **Bengaluru:** Lowest profit margin (-20.8%) and lowest total profit contribution (-0.3%).  

### **Top Customers & Products**  
- **Biggest Customer:** Electricalsara Stores (₹413M in 4 years).  
- **Best-Selling Product:** Prod318 (₹69M revenue in 4 years).  
- **Revenue by Product Type:**   
  - **Distribution:** ₹494M  
  - **Own Brand:** ₹494M  

### **Trend Analysis**  
- **June 2020:** Significant revenue drop compared to the previous year.  
- **April 2020:** Lowest profit margin recorded.  

## **Key Learnings**  
- Gained hands-on experience working with **real-world business datasets**.  
- Developed advanced **SQL querying** skills for analysis.  
- Learned how to **connect databases to Power BI** and clean data efficiently using **Power Query**.  
- Acquired practical knowledge of **DAX functions and measures**.  
- Built expertise in **creating insightful visual reports** for business intelligence.  
