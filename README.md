
This is a repository for my Data Analysis / Data Science portfolio projects. 

# Project 1: Exploratory Data Analysis of coffee sales data.
[CoffeeRawData.xlsx](https://github.com/user-attachments/files/17027033/CoffeeRawData.xlsx)
[CoffeeProject.xlsx](https://github.com/user-attachments/files/17027028/CoffeeProject.xlsx)
[CoffeeDashboard.pdf](https://github.com/user-attachments/files/17026913/CoffeeDshboard.pdf)
[Coffee_Sales_Analysis_Presentation_Styled.pptx](https://github.com/user-attachments/files/17040331/Coffee_Sales_Analysis_Presentation_Styled.pptx)

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
- **Order Date**: Order ID, Order date, Quantity ordered.
- **Product Information**: Product ID, Type of coffee, roast type, and package size.
- **Customer Information**: Customer name, E-mail, Phone number, Address, Loyalty card status and geographical location (countries).
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
   - A bar chart illustrates sales distribution by country (e.g., United States, United Kingdom, Ireland).
   - **Key Insight**: The **United States and United Kingdom** dominated the sales, while **Ireland** contributed a smaller share. This information can guide localized marketing strategies to boost sales in underperforming regions.

#### f. **Top Purchasing Customers**
   - A table highlighting the top 5 customers based on total sales value.
   - **Key Insight**: A small percentage of customers contribute significantly to overall revenue, indicating that personalized marketing and exclusive offers could help retain and grow this high-value customer segment.

---

### 5. **Key Insights and Business Recommendations**

Based on the analysis, the following key insights and recommendations were derived:

#### a. **Increase Promotions in Low-Sales Months**
   - January and February consistently show lower sales volumes. The business could implement seasonal promotions, discounts, or marketing campaigns targeting this slow period to combat this.

#### b. **Target Customer Loyalty Programs**
   - High-value customers and those with loyalty cards significantly contribute to overall sales. Expanding loyalty programs with personalized rewards and offers could increase customer retention and encourage repeat purchases.

#### c. **Focus on Popular Product Sizes**
   - The 0.5 kg and 1.0 kg packages are the most popular. The business should focus on these sizes in its marketing efforts and discontinue less popular sizes like 2.5 kg.

#### d. **Boost Sales in Underperforming Countries**
   - Sales are concentrated in the United States and the United Kingdom, while Ireland lags behind. Implementing localized promotions or exploring partnerships with coffee retailers in Ireland could help grow the market share there.

#### e. **Revise Underperforming Product Offerings**
   - Liberica and Excelsa coffee types, as well as smaller and larger package sizes, performed poorly. The company could either improve the taste and marketing of these products or consider reducing their presence in stores.

---

### 6. **Conclusion**

This Exploratory Data Analysis (EDA) of coffee sales data provides valuable insights into business performance, customer preferences, and product trends. The findings can help inform marketing strategies, optimize product offerings, and enhance customer loyalty programs. By focusing on the identified areas of opportunity, the business can maximize its profitability and continue to grow in an increasingly competitive market.

---

# Project 2: Exploratory Data Analysis of Human Resources (HR) data.

[HR.Data.csv](https://github.com/user-attachments/files/17042874/HR.Data.csv)
[hr_report.pdf](https://github.com/user-attachments/files/17042873/hr_report.pdf)
[HR Data.csv](https://github.com/user-attachments/files/17042872/HR.Data.csv)
[Percentage_Hire_Change.csv](https://github.com/user-attachments/files/17042871/Percentage_Hire_Change.csv)
[State distribution.csv](https://github.com/user-attachments/files/17042869/State.distribution.csv)
[age group distribution by gender.csv](https://github.com/user-attachments/files/17042868/age.group.distribution.by.gender.csv)
[employee_hire_count.csv](https://github.com/user-attachments/files/17042867/employee_hire_count.csv)
[employee_state_distribution.csv](https://github.com/user-attachments/files/17042866/employee_state_distribution.csv)
[hr_query.pdf](https://github.com/user-attachments/files/17042865/hr_query.pdf)
[job_title_distribution.csv](https://github.com/user-attachments/files/17042864/job_title_distribution.csv)
[remote_employees.csv](https://github.com/user-attachments/files/17042863/remote_employees.csv)
[tenure_department.csv](https://github.com/user-attachments/files/17042862/tenure_department.csv)
[turnover rate.csv](https://github.com/user-attachments/files/17042861/turnover.rate.csv)


### 1. **Introduction**

This project provides an in-depth exploration of human resources data using SQL for analysis and Power BI for dynamic visualizations. It uncovers critical insights into key HR metrics such as employee turnover, diversity, recruitment efficiency, and performance evaluations. By creating interactive dashboards, the analysis equips HR professionals with the tools to make data-driven decisions and formulate strategic workforce planning initiatives. These insights are crucial for enhancing organizational effectiveness, optimizing talent management, and driving informed business strategies. This report covers the entire process, from **dataset cleaning** to **visualization, reporting, and deriving key business insights**.

#### Tool
      MS SQL SERVER 2022 and MS POWER BI

### 2. **Dataset Overview**
      The data contains 22,000 Human Resource records from 2000 to 2020. [HR Data.csv](https://github.com/user-attachments/files/17043154/HR.Data.csv)

The dataset includes the following key attributes:

- **Employee Information**: Employee ID, Name, Age, Gender, Department, and Position.
- **Employment Dates**: Hire date, End date (if applicable), and Tenure.
- **Performance Metrics**: Performance rating, Promotions, and Salary changes over time.
- **HR Metrics**: Employee turnover status, Diversity metrics, and Recruitment effectiveness.
- **Compensation and Benefits**: Salary, Bonus, and Benefits packages.
- **Other Information**: Training completion, Employee satisfaction score, and Office location (remote or on-site).

### 3. **Data Cleaning Process**

Before conducting the analysis, it was crucial to clean and prepare the dataset. Here are the key steps involved in the data-cleaning process:

#### a. **Handling Missing Values**
   - Missing values were identified in fields such as employee tenure, performance ratings, and salary.
   - For numeric fields (like tenure and salary), missing values were imputed using the median to maintain the integrity of the data distribution.
   - Categorical fields (such as department or job title) were assigned a default category, such as "Unknown," to prevent information loss.

#### b. **Removing Duplicates**
   - Identified and removed duplicate employee records to ensure unique entries for each employee.
   - Ensured no repeated entries for the same employee over time unless they represented valid data (e.g., rehire after a break).

#### c. **Correcting Data Types**
   - Ensured that date fields (hire date, end date) were formatted correctly as `DateTime`.
   - Converted numerical fields like salary, bonuses, and performance scores to their appropriate data types for accurate calculations.

#### d. **Dealing with Outliers**
   - Outliers in salary and performance scores were examined using interquartile range (IQR) methods.
   - Extreme values, such as abnormally high bonuses or unusually low-performance scores, were reviewed and handled to avoid skewing the analysis.

#### e. **Standardizing Formats**
   - Standardized department names, job titles, and other categorical fields to maintain consistency in grouping and reporting.
   - Ensured consistent formatting of text fields like employee names and job titles to avoid issues during aggregation and analysis.
---

### 4. **Data Visualization and Reporting** [hr_report.pdf](https://github.com/user-attachments/files/17043831/hr_report.pdf)


Questions:
1.  What is the age distribution in the company?
2.  What is the gender breakdown in the company?
3.  How does gender vary across departments and job titles?
4.  What is the race distribution in the company?
5.  What is the average length of employment in the company?
6.  Which department has the highest turnover rate?
7.  What is the tenure distribution for each department?
8.  How many employees work remotely for each department?
9.  What is the distribution of employees across different states? 10. How are job titles distributed in the company?
10. How have employee hire counts varied over time?
    
Results:
Demographic and Employment Insights:

1.  The company has a higher number of male employees compared to female or non-conforming individuals.
2.  Gender distribution is relatively even across departments, although there is a slight overall prevalence of male employees.
3.  The 21-30 age group has the fewest employees, with the majority falling within the 31-50 age range. Surprisingly, the 50-and-over 
    age group constitutes the largest segment of the workforce.
4.  Most employees are of Caucasian ethnicity, followed by mixed race, black, Asian, Hispanic, and Native American backgrounds.
5.  On average, employees have a tenure of 7 years with the company.
6.  Auditing experiences the highest turnover rate, followed by Legal, Research & Development, and Training. Business Development & 
    Marketing exhibits the lowest turnover rates.
7.  Employee tenure is typically 6-8 years, with a fairly even distribution across departments.
8.  Approximately 25% of employees work remotely.
9.  Ohio has the highest employee concentration (14,788), followed by Pennsylvania (930), Illinois (730), Indiana (572), Michigan 
   (569), Kentucky (375), and Wisconsin (321).
10. The company boasts 182 job titles, with Research Assistant II having the highest count (634). In contrast, positions l 
    like Assistant Professor, Marketing Manager, Office Assistant IV, Associate Professor, and VP of Training and Development each 
    have only one employee.
11. Over the years, there has been an increase in employee hiring counts.
---

### 5. **Conclusion**

This Exploratory Data Analysis (EDA) of the HR dataset provides valuable insights into employee turnover, diversity metrics, and overall workforce performance. The findings can inform HR policies, improve recruitment strategies, and enhance employee retention programs. By addressing the identified trends in turnover and performance, the organization can foster a more inclusive and productive work environment, leading to improved employee satisfaction and long-term success. These insights are crucial for optimizing workforce management and driving organizational growth in an increasingly competitive landscape.



---





