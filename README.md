# Amazon-Product-Review-Analysis
🔍 E-commerce Analytics: Product & Review Insights
As a Junior Data Analyst at RetailTech Insights, I contribute to developing data-driven solutions for e-commerce sellers on platforms like Amazon. This project involves analyzing product and customer review data to uncover actionable insights that drive product improvements, sharpen marketing strategies, and enhance customer engagement.

## 📊 Project Title: Amazon-Product-Review-Analysis

### 🔍 [Project Overview](#project-overview)

This project leverages **Microsoft Excel** to perform exploratory data analysis on Amazon product reviews, aiming to uncover actionable insights for online sellers. As a Junior Data Analyst at RetailTech Insights, my role involves cleaning, organizing, and visualizing customer review data to highlight trends in ratings, sentiment, and buyer feedback. By focusing on Excel’s capabilities—like pivot tables, charts, lookup functions, and conditional formatting—we transform raw review data into strategic insights that can inform product enhancements, guide marketing direction, and improve customer engagement on Amazon’s marketplace.
This project was developed as part of the **DSA Capstone** on data analysis and contributes to my ongoing **upskilling in data analytics**.

### 📁 Data Sources  
- Sourced from the DSA Class materials provided for capstone analysis and training.
- `Amazon case study$`  
These datasets were sourced from the DSA platform’s LMS and provided by the course facilitators.
---
### 🗂️ Dataset Description

The dataset contains structured information scraped from Amazon product pages. It includes both product attributes and customer engagement data, summarized as follows:

- **Product Details**:  
  - Name  
  - Category  
  - Price  
  - Discount  
  - Ratings  

- **Customer Engagement**:  
  - User review titles and full content  
  - Review sentiment (if applicable)  

- **Structure**:  
  - Each row represents a unique product  
  - Aggregated reviewer data is stored as comma-separated values within relevant fields
 
![Screenshot 2025-07-04 223824](https://github.com/user-attachments/assets/14e4aa0b-f83f-45ca-bf28-20dc66625b42)

---
### 🛠 Tools Used  
- **Microsoft Excel 365** – for preliminary exploration, for data cleaning, modeling, and visualization 

### 🧹 Data Cleaning & Preparation  
Performed in Excel using Power Query. Key cleaning steps included:
- Removal of duplicate and incomplete records  
- Splitting of Prodcut column using flash fill
---
### 🛠 Tools Used  
- [Microsoft Excel](http://www.microsoft.com) – Initial data review and inspection, Data cleaning and visualization  
- **Github** – Portfolio building and version control

---

### 🧹 Data Cleaning & Preparation  
Conducted using Excel. Key steps included:  
1. Data loading and inspection  
2. Handling missing values and inconsistencies  
3. Data formatting for analysis readiness

---

### 🔍 Exploratory Data Analysis (EDA)  
Key business questions explored during EDA uisng Pivot Table were:  
1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category?
4. Which products have the highest average ratings?
5. What is the average actual price vs the discounted price by category?
6. Which products have the highest number of reviews?
7. How many products have a discount of 50% or more?

---

### 📊 Data Visualization  

**Excel Dashboard Visual Snapshot**  
![Screenshot 2025-07-04 223722](https://github.com/user-attachments/assets/09872c4f-c324-4004-81b2-2531a37de43f)

---


### 🧠 Data Analysis  
Sample DAX expressions used in Power BI analysis:

```Excel Function used
-- RATING_CATEGORY
=IFS(H2<=1,"1.0",H2<=2,"2.0",H2<=3,"3.0",H2<=4,"4.0",H2<=5,"5.0")

-- PRICE BUCKET
=IFS(F2<200,"<200",F2<=500,"200 – 500",F2>500,">500")

```

---

### 📎 Files Used  
- [Palmoria Group emp-data$](./Palmoria%20Group%20emp-data.csv) *(Palmoria Group emp-data.csv)*
- [Palmoria Group Bonus Rules$](./Palmoria%20Group%20Bonus%20Rules.xlsx) *(Palmoria Group Bonus Rules.xlsx)*
- 

### 📂 Project Files

- 📊 [Power BI Report – DSA Project: Palmoria HR Analysis.pbix](https://github.com/your-username/your-repo-name/blob/main/DSA%20Project%20-%20Palmoria%20HR%20Analysis.pbix?raw=true)

---
