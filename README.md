
# ☕ Coffee Shop Sales Analysis
Sales performance analysis of a coffee shop chain using Excel. Includes data cleaning, visualization, and insights on store performance, monthly trends, and top-selling product categories.

## 📚 Table of Contents
- [☕ Coffee Shop Sales Analysis](#-coffee-shop-sales-analysis)
- [📊 Project Overview](#-project-overview)
- [🧮 Key Variables](#-key-variables)
- [❓ Research Questions](#-research-questions)
- [🧹 Data Cleaning Summary](#-data-cleaning-summary)
- [🏪 Which Store Location Generated the Highest Total Sales?](#which-store-location-generated-the-highest-total-sales)
- [📅 Which Month Recorded the Highest Overall Sales?](#which-month-recorded-the-highest-overall-sales)
- [💰 Which Product Category Contributes Most to Total Revenue?](#which-product-category-contributes-most-to-total-revenue)
- [⚠️ Limitations of the Analysis](#limitations-of-the-analysis)
- [💡 Recommendations for Improvement](#recommendations-for-improvement)
- [✅ Conclusion](#conclusion)

---

## 📊 Project Overview
This project analyzes 2023 sales transactions from a chain of coffee shops across three locations:
- Hell's Kitchen  
- Astoria  
- Lower Manhattan  

Each record contains the **product type**, **amount sold**, **unit price**, **transaction date**, **store location**, and **total sales**.  
The goal is to identify the **best-performing store**, **peak month**, and **top-selling product categories**.

**Dataset Source:** [Coffee Shop Sales Dataset – Kaggle](https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales)  
**Dataset Size:** 1,490 rows × 7 columns

---

## 🧮 Key Variables
| Variable | Description |
|-----------|-------------|
| Date | Transaction date |
| Store Location | Shop branch (Hell’s Kitchen, Astoria, etc.) |
| Product Category | Type of item sold |
| Quantity | Number of units sold |
| Unit Price | Price per unit |
| Total Sales | Calculated as `Quantity × Unit Price` |

---

## ❓ Research Questions
1. Which store location generated the highest total sales?  
2. Which month recorded the highest sales?  
3. Which product category contributes most to total revenue?

---

## 🧹 Data Cleaning Summary
Performed using **Power Query (Excel)**

- Checked for duplicates or missing values  
- Verified proper date formatting  
- Ensured numeric fields for Quantity and Unit Price  
- Created calculated column:  
  ```excel
  Total Sales = Quantity × Unit Price
- The final dataset was consistent, tidy and prepared for analysis in Excel

---

### Which Store Location Generated the Highest Total Sales?

<img width="963" height="736" alt="image" src="https://github.com/user-attachments/assets/25194350-a554-41dc-aaa1-65053459f29c" />

- At **₦236,511.17**, the **Hell's Kitchen** location recorded the **highest overall sales**, slightly surpassing **Astoria** and **Lower Manhattan**.  
- The differences among the three branches are **negligible**, indicating that performance is generally **balanced across all locations**.  
- The consistent lead of **Hell's Kitchen** suggests **stronger marketing strategies** or **higher customer traffic** at that branch.

### Which Month Recorded the Highest Overall Sales?

<img width="933" height="856" alt="image" src="https://github.com/user-attachments/assets/75c4d31a-1d41-4096-b36b-6ee06fe334e1" />

- **June** recorded the **highest total sales** at **₦166,485.88**, followed closely by **May** with **₦156,727.76**.  
- This indicates that the **second quarter (Q2)** experienced a significant growth trend, likely due to increased consumer activity during the warmer months.  
- **February** had the **lowest sales (₦76,145.19)**, suggesting a slower start to the year following the holiday season.  
- Overall, sales showed a **steady upward trend from January to June**, reflecting consistent business growth in the first half of 2023.

### Which Product Category Contributes Most to Total Revenue?

<img width="982" height="920" alt="image" src="https://github.com/user-attachments/assets/2abd147c-7e0b-4aaa-afbe-c9ae4b0f6644" />

- The **Coffee** category generated the **highest revenue**, contributing approximately **39%** of total sales.  
- **Tea** followed with **28%**, showing that customers have a strong preference for **hot beverages**.  
- **Bakery (12%)** and **Drinking Chocolate (10%)** were mid-performing categories that also made notable contributions.  
- Lower-performing categories such as **Packaged Chocolate (0.6%)**, **Loose Tea (1.6%)**, **Flavours (1.2%)**, and **Branded Goods (1.9%)** accounted for less than **6%** of total sales.  
- This suggests opportunities for **product simplification** or **targeted marketing** to boost the performance of underperforming categories.

### Limitations of the Analysis

- **Restricted Time Range:** The dataset only includes transactions from a single year (2023), making it difficult to analyze long-term or seasonal sales patterns.  
- **Absence of Customer Demographics:** The dataset lacks information such as customer age, gender, or loyalty status, which could provide deeper insights into purchasing behavior.  
- **Single Data Source:** The analysis is based on data from a single coffee shop chain and may not represent the broader café industry.  
- **Price Stability Assumption:** The dataset assumes constant pricing throughout the year and does not account for discounts, promotions, or price changes.

---

### Recommendations for Improvement

- **Add More Years of Data:** Incorporate multiple years of sales data to identify trends, seasonality, and long-term performance.  
- **Include Customer Demographics:** Adding customer-level data (e.g., age, gender, loyalty membership) would enable segmentation and personalized marketing strategies.  
- **Monitor Discounts and Promotions:** Tracking promotional activities would allow for better measurement of marketing effectiveness and its impact on sales volume.  
- **Use Advanced Visualization Tools:** Future iterations of this analysis could leverage tools like **Power BI** or **Tableau** for interactive dashboards and deeper insights.

---

### Conclusion

- **Hell’s Kitchen** recorded the **highest total sales**, showing slightly better performance than Astoria and Lower Manhattan.  
- **June** achieved the **peak sales month**, indicating opportunities to replicate factors that drove strong mid-year performance.  
- **Coffee** and **Tea** remain the **top revenue-generating categories**, highlighting consistent customer demand for hot beverages.  
- Overall, the coffee shop chain demonstrates **steady growth** but could further improve profitability by focusing on **underperforming product categories** and **enhanced data tracking**.

---


