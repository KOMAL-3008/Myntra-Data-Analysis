# **Myntra Apparel Analysis**  

## **Project Overview**  
This project focuses on analyzing a dataset from **Myntra**, a leading online fashion retailer in India. The dataset contains details of various apparel items, including prices, discounts, ratings, and available sizes. The goal is to clean the data, perform analysis, and extract actionable insights to help Myntra optimize its pricing strategies, discount patterns, customer ratings, and size availability.  

---

## **Problem Statement**  
As a data analyst, the task was to analyze the dataset to provide insights on:  
- Pricing strategies for high-rated products.  
- Discount patterns and their impact on sales.  
- Size availability to improve inventory management.  
- Customer ratings to identify popular products.  

The analysis aims to support data-driven decision-making for Myntra’s management team.  

---

## **Project Tasks**  

### **A. Data Cleaning & Preparation**  
1. **Duplicate Removal**: Removed duplicate entries to ensure data accuracy.  
2. **Standardize Discounts**: Converted all discount values (both percentage and flat Rs. discounts) into a uniform format.  
3. **Handle Missing Data**:  
   - Filled missing "DiscountPrice" values with the average discount price for that category.  
   - Replaced null values in the "SizeOption" column with "Not Available."  

### **B. Data Analysis**  
1. **Average Price for High-Rated Products**: Calculated the average original price for products with ratings > 4.  
2. **High Discounts**: Counted the number of products with discounts greater than 50%.  
3. **Size M Availability**: Counted the number of products available in size "M."  
4. **Discount Labeling**: Added a new column to label products as "High Discount" (above 50%) or "Low Discount" (50% or below).  

### **C. Data Retrieval & Lookup**  
1. **Product Lookup**: Used **VLOOKUP/XLOOKUP** to retrieve brand, price, and rating details for specific products.  
2. **Discount Lookup**: Applied **INDEX and MATCH** to find the discount price of a product.  
3. **Nested Lookup**: Implemented **nested XLOOKUP** to retrieve any product details based on product ID.  

---

## **Tools Used**  
- **Microsoft Excel**: For data cleaning, analysis, and advanced lookup functions.  
- **PowerPoint**: For creating a visually appealing presentation of insights.  

---

## **Key Insights**  
1. Identified pricing trends for high-rated products.  
2. Highlighted products with significant discounts (>50%) to attract more customers.  
3. Analyzed size availability to improve inventory management and customer satisfaction.  

---

This **README file** provides a clear and structured overview of your project, making it easy for others to understand and navigate. Let me know if you’d like to tweak it further! 😊
