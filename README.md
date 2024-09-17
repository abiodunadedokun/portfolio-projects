This repository contains my Data Analysis / Data Science portfolio projects. 

# Project 1: Exploratory Data Analysis of coffee sales data.
[CoffeeRawData.xlsx](https://github.com/user-attachments/files/17027033/CoffeeRawData.xlsx)
[CoffeeProject.xlsx](https://github.com/user-attachments/files/17027028/CoffeeProject.xlsx)
[CoffeeDashboard.pdf](https://github.com/user-attachments/files/17026913/CoffeeDshboard.pdf)

This project comprehensively analyses coffee sales data from 2019 to 2022, focusing on identifying key sales trends, understanding customer behavior, and evaluating product performance. The primary objective is to gain actionable insights to improve business strategies, optimize sales, and enhance customer engagement.

#### Tool
      Microsoft Excel 2019

### Coffee Sales Data Analysis Project Report

---

### 1. **Introduction**

This project is a comprehensive **Exploratory Data Analysis (EDA)** of coffee sales data from 2019 to 2022. The primary aim is to uncover patterns, customer behaviors, product performance, and trends that can drive business decisions and enhance sales strategies. This analysis provides insights into the overall sales performance, top customers, and product preferences, which can be crucial for optimizing business operations.

This report covers the entire process, from **dataset preparation and cleaning** to **visualization, reporting, and deriving key business insights**.

---

### 2. **Dataset Overview**

The dataset includes the following key attributes:
- **Order Date**: The date each order was placed.
- **Product Information**: Type of coffee, roast type, and package size.
- **Customer Information**: Loyalty card status and geographical location (countries).
- **Sales Information**: Quantity sold, revenue generated from each order.

---

### 3. **Data Cleaning Process**

Before conducting the analysis, it was crucial to clean and prepare the dataset. Here are the key steps involved in the data-cleaning process:

#### a. **Handling Missing Values**
   - Missing values were identified in the sales and customer details.
   - Numeric fields (such as sales quantities) were imputed using the median to prevent data skewing.
   - Missing categorical values (such as coffee types or loyalty card status) were categorized as "Unknown."

#### b. **Removing Duplicates**
   - Checked for duplicate rows in customer and order data.
   - Removed duplicate entries to ensure the analysis reflects unique transactions and customer interactions.

#### c. **Correcting Data Types**
   - Ensured that date fields were correctly formatted as `DateTime`.
   - Converted numerical fields to the appropriate data types (e.g., quantities and sales values as floats).

#### d. **Dealing with Outliers**
   - Identified and handled outliers in sales amounts using interquartile range (IQR) methods.
   - Extreme outliers, such as extraordinarily high or low sales values, were investigated and adjusted if necessary to avoid misleading trends.

#### e. **Standardizing Formats**
   - Standardized text formats (e.g., making product names consistent) to facilitate proper grouping and analysis.

---

### 4. **Data Visualization and Reporting**

Various visualizations were created using Excel to extract valuable insights from the dataset. These visualizations help to understand sales performance, product popularity, and customer behavior across different dimensions.

#### a. **Total Sales Over Time**
   - A line graph showing the monthly total sales from 2019 to 2022 was created to identify trends and seasonality.
   - **Key Insight**: Sales steadily increased over the years, with **June consistently showing the highest sales**, likely driven by seasonal promotions. **January and February** showed the lowest sales, suggesting a post-holiday slowdown.

#### b. **Product Performance by Coffee Type**
   - A slicer displaying sales by coffee type (e.g., Arabica, Robusta, Liberica, Excelsa).
   - **Key Insight**: **Arabica and Robusta** were the most popular coffee types, accounting for the largest portion of sales, while **Liberica and Excelsa** had lower sales volumes, suggesting they cater to niche markets.

#### c. **Sales by Product Size**
   - Sales were visualized by product size (0.2 kg, 0.5 kg, 1.0 kg, and 2.5 kg).
   - **Key Insight**: **0.5 kg and 1.0 kg packages** were the most popular, indicating that customers prefer medium-sized purchases. Smaller and larger sizes performed less well.

#### d. **Customer Loyalty Analysis**
   - A slicer showing the impact of sales contributed by loyalty card holders versus non-loyalty card holders.
   - **Key Insight**: Customers with **loyalty cards** made more frequent and higher-value purchases, suggesting that expanding loyalty programs could drive repeat business.

#### e. **Sales by Country**
   - A bar chart was used to illustrate sales distribution by country (e.g., United States, United Kingdom, Ireland).
   - **Key Insight**: The **United States and United Kingdom** dominated the sales, while **Ireland** contributed a smaller share. This information can guide localized marketing strategies to boost sales in underperforming regions.

#### f. **Top Purchasing Customers**
   - A table highlighting the top 5 customers based on total sales value.
   - **Key Insight**: A small percentage of customers contribute significantly to overall revenue, indicating that personalized marketing and exclusive offers could help retain and grow this high-value customer segment.

---

### 5. **Key Insights and Business Recommendations**

Based on the analysis, the following key insights and recommendations were derived:

#### a. **Increase Promotions in Low-Sales Months**
   - January and February consistently show lower sales volumes. To combat this, the business could implement seasonal promotions, discounts, or marketing campaigns targeting this slow period.

#### b. **Target Customer Loyalty Programs**
   - High-value customers and those with loyalty cards significantly contribute to overall sales. Expanding loyalty programs with personalized rewards and offers could increase customer retention and encourage repeat purchases.

#### c. **Focus on Popular Product Sizes**
   - The 0.5 kg and 1.0 kg packages are the most popular. The business should focus on these sizes in its marketing efforts and possibly discontinue less popular sizes like 2.5 kg.

#### d. **Boost Sales in Underperforming Countries**
   - Sales are concentrated in the United States and the United Kingdom, while Ireland lags behind. Implementing localized promotions or exploring partnerships with coffee retailers in Ireland could help grow the market share there.

#### e. **Revise Underperforming Product Offerings**
   - Liberica and Excelsa coffee types, as well as smaller and larger package sizes, performed poorly. The company could either improve the taste and marketing of these products or consider reducing their presence in stores.

---

### 6. **Conclusion**

This **Exploratory Data Analysis (EDA)** of coffee sales data provides valuable insights into business performance, customer preferences, and product trends. The findings from this analysis can help inform marketing strategies, optimize product offerings, and enhance customer loyalty programs. By focusing on the identified areas of opportunity, the business can maximize its profitability and continue to grow in an increasingly competitive market.

---




