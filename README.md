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
Some Excel Functions used in Power BI analysis:

```Excel Function used
-- RATING_CATEGORY
=IFS(H2<=1,"1.0",H2<=2,"2.0",H2<=3,"3.0",H2<=4,"4.0",H2<=5,"5.0")

-- PRICE BUCKET
=IFS(F2<200,"<200",F2<=500,"200 – 500",F2>500,">500")

```
### Insight from the Analysis
---

### 📖 Insights-Driven Storytelling: From Data to Decisions
When customers speak—through ratings, reviews, and patterns in their behavior—they’re offering more than just praise or complaints. They're handing us a playbook for innovation, brand loyalty, and smarter marketing. In this Excel-based analysis of Amazon product reviews, I explored thousands of data points to uncover what customers truly value, where sellers are overplaying their hand, and how Amazon can stay ahead in an ever-evolving marketplace.

---
#### 🛠️ Product Improvement: Tuning into the Consumer Pulse
From review volumes to average ratings, the data paints a clear picture: **customers respond best when value and quality are balanced**.
- **Top-performers like Computers & Accessories and Electronics not only dominate in volume but also enjoy strong customer sentiment**. This suggests Amazon’s algorithms are surfacing the right products—those with both demand and performance.
- Yet in categories like *Home Improvement* and *Health & Personalcare*, **steep discounting (up to 57.5%) contrasts with relatively low product representation**—a red flag for missed opportunities. These gaps reveal space to diversify listings and raise the bar on quality, not just price.
- Products with clustered 4.0–5.0 ratings hide the gray area: items that are “good enough” but not excellent. By digging deeper into 3–4 star reviews, sellers can uncover recurring product-specific complaints that are masked by strong averages.

**Proposal**: Launch a product quality initiative focused on mid-rated items to turn “good” into “great,” especially in underrepresented categories.

---

#### 📣 Marketing Strategy: Stop Discounting, Start Differentiating

With **751 products discounted 50% or more**, it’s clear that sellers are relying heavily on price slashing to win sales. While discounts work, they're a blunt instrument.

- **Categories like Home Improvement and Electronics see the deepest cuts, yet they also boast strong organic engagement**—signaling that quality and branding may be powerful enough to support more modest promotional strategies.
- Underrepresented but high-engagement categories (*Toys & Games* with 15K+ reviews but just 2 products listed) offer fertile ground for **targeted marketing campaigns** that spotlight value beyond price—like durability, innovation, or lifestyle alignment.

**Proposal**: Equip sellers with review-based marketing insights to highlight unique product attributes, shifting focus from discounts to differentiation.

---

#### 🤝 Customer Engagement: Beyond the Stars

Ratings are just the entry point. It's the **review narratives** that reveal what customers care about—durability, packaging, ease of use, compatibility.

- For top-tier products, many reviews praise features or ease of use. But mid-range reviews often hint at **expectation mismatches**, such as vague descriptions or lack of product guidance.
- Reviews mentioning **packaging issues, delayed delivery, or unclear instructions** appeared repeatedly, especially in tech categories.

**Proposal**: Incorporate review themes into customer support, packaging design, and product pages. A tighter feedback loop will make buyers feel heard and build brand loyalty.

---

#### 🔍 Conclusion: Listening, Learning, and Leading

This Excel-powered analysis doesn’t just crunch numbers—it tells a story. A story of what’s working, where Amazon sellers can evolve, and how customer voices shape tomorrow’s marketplace. Whether it’s expanding overlooked categories, refining marketing tactics, or improving product design, this analysis bridges the gap between data and decision-making.

---



---

### 📎 Files Used  
- 📂 [Download the Excel File – *Amazon case study - Analysis.xlsx*](Amazon%20case%20study%20-%20Analysis.xlsx)
-
### 📂 Project Files

- 📊 [Download the Excel File – *Amazon case study - Analysis.xlsx*](Amazon%20case%20study%20-%20Analysis.xlsx)

---
