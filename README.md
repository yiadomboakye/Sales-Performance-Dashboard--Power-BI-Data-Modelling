# Sales Performance Analysis

### Project Overview

Understanding the key factors that drive success is crucial for analyzing data and delivering meaningful insights to stakeholders and the organization. This project utilizes Power BI to model data and establish relationships between datasets. By creating measures and leveraging DAX functions such as SAMEPERIODLASTYEAR and EOMONTH, the objective is to help the company track and achieve its key performance indicators (KPIs) on a monthly, quarterly, and yearly basis.
Additionally, the project aims to identify high-performing products, highlight those requiring further attention, and assess the impact of different market segments, regions, and product categories on sales and profitability. It also analyses monthly sales and profit trends, providing strategic recommendations to drive revenue growth and enhance overall business performance.

### Data Sources
The dataset used for this project is the "Global_Superstore.csv" file. It contains detailed information on each sale made by the company, including order details, customer demographics, product categories, and financial metrics such as sales, profit, and discounts.
- [Dataset](https://github.com/yiadomboakye/Sales-Performance-Dashboard_-Power-BI/blob/main/Global_Superstore(CSV)%20(version%201).xlsb.csv)

### Tool Used
For this project, the following tools were utilized to analyse and visualize the dataset.
### Excel
Used for loading and inspecting data.
### Power Querry Editor
This was used for data transformation and cleaning, including tasks such as removing duplicates, changing data types, filtering and sorting, as well as creating dimensions and managing relationships.
### Power BI
Used for visualizing and creating charts.
### Power Point
Used to design backgrounds for the visuals. This was essential as stakeholders and companies often require a background that aligns with the company’s branding or design preferences.

### Exploratory Data Analysis
The Exploratory Data Analysis (EDA) focused on uncovering key insights from the sales data by addressing the following critical questions:

 - Did we meet our financial KPIs this year? If not, why?
 - 	Which product categories are performing well in terms of sales for each quarter of the year, and which ones are performing the least well?
 - 	What are our top 5 most valuable products in terms of sales?
 - 	What are the monthly sales and profit trends for previous year and this year?
 - 	What has been the impact of our market segments and regions on sales for last year and this year?
 - 	What is the net profit and net profit increase after additional charges this 
year?
Ship Mode Additional Charges on Sales Economy 1% Economy Plus 2% Immediate 3% Priority 5%
#### Data modelling
I built a star schema to optimize data modelling and analysis. The original dataset was transformed into a fact table containing transactional data, while four-dimension tables: Product, Geographic, Order, and Customer were created to provide descriptive context. These dimension tables were linked to the fact table using one-to-many relationships, ensuring efficient data retrieval and organization. Additionally, a date table was created and linked to the fact table. The date table was essential because I wanted to ensure accurate time-based analysis without missing dates and enable precise comparisons across different time periods. By incorporating a date table, I could effectively use time intelligence functions such as SAMEPERIODLASTYEAR to compare sales and profit across different time periods, ensuring reliable and meaningful insights. I also created a measure called Key Measures, which consolidated all the important calculated values, such as Sales Last Year, Sales Current Year, Profit Last Year, and Profit Current Year. This measure helped streamline the analysis, allowing me to easily compare and track performance across different time periods in a single, organized structure. 

![Star schema](https://github.com/user-attachments/assets/eba1fbf7-c5f6-4ff7-aa94-f4447fe839a3)

### Results/Findings

![Capture_ Power BI](https://github.com/user-attachments/assets/776db9c0-ab6b-40a8-bbed-832d32f9c68f)


- The company's financial KPIs showed an improvement over the previous year's results, which was a target the company set for this year.
- All three categories appear to contribute significantly to the company's growth this year, but the technology category proved to be the most efficient, while the office supplies category needs to be re-evaluated.
#### The top 5 most valuable products of the company by sales are:
- Motor Smart Phones
- Apple Phones
- Cisco Smart Phones
- Nokia Phones
- Samsung Phones
- The Asia market is the largest contributor to the company's sales, followed by Europe.
- The USCA and Africa markets are the least contributing to the company's sales growth.
- The company's peak sales periods last year occurred in the final quarter, with December achieving the highest sales.
- The company's peak sales periods in the current year occurred in the second quarter, but December achieved the highest sales.
- Lowest Sales for last year was in the month of July.
- Lowest Sales for the current year was in the months of March and July.
- Highest net profit for last year was in the months of February and June.
- Highest net profit for current year was in the month of October.
- Lowest net profit for last year and current year were both in September

  


