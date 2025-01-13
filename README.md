# Data-Mart_EDA
This project focuses on analyzing the sales performance of a retail business. As part of this case study, raw sales data table is cleaned, transformed, and analyzed using PostgreSQL. The project demonstrates essential data engineering and data analysis techniques, showcasing the use of SQL for real-world business insights.

---
## Skills Demonstrated
### 1. **SQL Expertise**
   - Wrote complex SQL queries to clean, transform, and analyze the dataset.
   - Designed queries that are efficient and scalable for real-world applications.
   - Used advanced SQL features like **window functions**, **conditional logic**, and **aggregations** to derive insights.

### 2. **Data Cleaning**
   - Ensured data consistency by transforming raw data into a cleaned format.
   - Handled missing values and applied logical mappings to enhance dataset usability.
   - Created calculated columns such as `avg_transaction` and categorized customer demographics into meaningful groups.

### 3. **Data Analysis**
   - Explored trends in sales performance across multiple dimensions:
     - Weekly trends
     - Regional and platform-based comparisons
     - Demographic-based performance analysis
   - Delivered actionable insights using SQL queries to answer business-critical questions.

---

## Case Study Objectives
The main objectives of the case study are:
1. **Data Cleaning:** 
   - Add new derived columns like `week_number`, `month_number`, and `calendar_year`.
   - Categorize `segment` values into `age_band` and `demographic` groups.
   - Replace null values with `"unknown"` for certain fields.
   - Calculate the average transaction value as `avg_transaction` for each record.

2. **Data Exploration:** 
   - Identify missing weeks in the dataset.
   - Analyze transactions and sales across various dimensions like years, regions, platforms, and demographics.
   - Calculate percentages and contributions to sales by platform and demographic categories.

3. **Key Business Questions Answered:**
   - Which regions performed the best after adopting sustainable practices?
   - How did customer demographics influence sales performance?
   - Which platforms contributed the most to overall transactions and revenue?

---
## How to Use
1. **Database Setup:**
   - Load the `WEEKLY_SALES` table schema into your PostgreSQL database.
   - Populate the table with the provided raw data (as per the case study document).

2. **Run the SQL Script:**
   - Execute the queries sequentially those which are attached. 
   - The script performs data cleaning and analysis tasks to generate the required insights.

3. **Explore Results:**
   - Review the outputs of each query to answer the business questions listed in the case study.

---
## Future Work
This analysis lays the groundwork for more advanced explorations. Future work could include:
- Building interactive dashboards using tools like Tableau or Power BI.
- Incorporating machine learning models to forecast sales trends.
- Expanding the dataset to include more variables, such as customer feedback or product categories.




