# Project Title: Bike Racks Sales Analysis 

## Overview

This project focuses on analyzing sales and marketing strategies for bike rack sales, with a strong emphasis on key metrics and specific business requirements. By leveraging data-driven insights, the aim is to provide well-informed, actionable strategies that enhance inventory management and boost overall sales. Through this analysis, we strive to uncover valuable trends and opportunities that will support more effective marketing and inventory decisions, ensuring sustained growth in both bike rack and accessory sales.

### Objectives 

This project focuses on analyzing the following business problem 

- Revenue Distribution by Region: Analyze which countries and states generate the most revenue for bike rack sales.
and target specific regions for promotional campaigns to boost sales in high-revenue areas and address underperforming regions for improvements.
- Demographic by age group: Segment customers into eg(less than 25yrs as "Youth", 24-35yrs "Young Adult", more than 35yrs "Adult" to know which age group patronize the most and tailor marketing strategies to target specific age groups and genders, optimizing product appeal for the key demographic segments.
- Product Popularity: Assess the performance of different models of bike racks (e.g., "Hitch Rack - 4-Bike") in terms of sales volume. Inorder to refine product offerings, adjust inventory, and promote best-selling items to maximize profit.
- Sales Seasonality: Analyze trends in bike rack sales across different times of the year and correlate them with external factors like holidays or cycling season, thereby planning inventory and marketing efforts according to seasonal peaks and troughs, ensuring sufficient stock during high-demand periods and reducing excess inventory during low-demand months.

### Key Performance indicator (KPIs)

- Total Revenue: The total sales generated by the store.
- Order Quantity: The total number of units sold, broken down by product type and customer demographic.
- Total Profit: The earnings after deducting the cost of goods sold (COGS) and other operating expenses.

### Data Source
The dataset used for this analysis was obtained from excel and can be accessed using this link. [Download Here](https://www.microsoft.com)

### Tool used 
Microsoft Excel 
 1. For data cleaning
 2. For Analysis
 3. For visualization

### Steps followed 
 1. Data cleaning: The raw data collected was first processed to ensure its integrity, consistency, and quality, setting a strong foundation for effective analysis and visualization.
- Data filtering and missing values: I began by addressing missing entries. For numerical fields such as quantity or age, I checked for outliers. If outliers were detected, I filled the blanks using the median or mode; if no outliers were present, I filled them with the average value.
- For categorical variables like gender, country, or state, I utilized a nested IF function to logically fill in the blanks based on existing data.
- Correcting Misspellings: I conducted a review of the dataset to identify any misspelled words or inconsistencies in text fields, replacing incorrect terms with the appropriate ones to maintain uniformity.
- Standardizing Formats: I ensured that all relevant fields, such as Revenue, unit_price and dates, were formatted consistently to facilitate smooth analysis.
- Sorting the Data: I organized the data according to relevant criteria, whether alphabetically (A to Z or Z to A) or chronologically (from oldest to newest or vice versa), to enhance readability and trend identifications.
- Removing Duplicates: I removed duplicate records to maintain data accuracy and integrity.
-Structuring for Analysis: Finally, I converted the cleaned data into a structured table format, making it ready for analysis using pivot tables.
2. Data analysis: In this phase, I leveraged pivot tables in Excel to summarize and analyze the data in alignment with key performance indicators (KPIs) and specific business requirements, always keeping the broader business objectives in mind. I used filters where needed to ensure the analysis was tailored and focused.
- I created a variety of charts, including bar charts, column charts, pie charts and line charts which helped bring the data to life, making it easier to spot trends, compare metrics, and uncover insights that support strategic decision-making. I also added slicers, allowing for dynamic filtering of the data, making it easier to interact with the information and drill down into specific segments as needed.
3. Data visualization: In this phase, I crafted an interactive dashboard that brought together all the essential charts, slicers, KPIs, and the business name, arranging each element thoughtfully to ensure clarity and impact. This dashboard provided a one-stop view of the data, making it easy to spot key trends and business challenges at a glance.
- With a clear view of the business’s pain points, I was able to provide actionable recommendations aimed at addressing these areas and drive growth. The dashboard wasn’t just a set of visuals; but a tool designed to empower decision-making, transforming data into insights and strategies that can elevate the business to the next level.

## Data Visualization and Insights
"To explore the dataset, I utilize a pivtot table to summarize the KPI and Business Requirement which was then transformed into a chart for better clarity and presentation."

#### Revenue Distribution by Region

![Screenshot 2024-12-10 145356](https://github.com/user-attachments/assets/42efb3af-d6d1-4fca-9186-da46741b7589)


The United State generates the highest revenue followed by Canada, France, Australia, Germany and finally United Kingdom, which records the lowest revenue. 

##### State-Level Analysis

- United State (3 states)

California generates the higest revenue of $129,840 and Kentucky generates the lowest revenue of $240.

- Canada (2 states)

British Columbia generates the higest revenue of $99,000 and Alberta generate the lowest revenue of $2,640.

- France (10 states)

Nord generates the higest revenue of $31,304 and Loir et Cher generates the lowest revenue of $1,440.

- Australia (4 states)

New South Wales generates the higest revenue of $25,200 and South Australia generates the lowest revenue of $10,080.

- Germany (5 states)

Bayern generates the higest revenue of $17,166 and Hamburg generates the lowest revenue of $5,280.

- United Kingdom (1 state)

England and it generates a total revenue of $49,080.


![image](https://github.com/user-attachments/assets/889f4c82-7998-4b94-bf59-ba67572c624e)

### Inference:

- It seen that California and British Columbia genetate the most revenue which could be because of their strong emphasis of onenvironmental sustainability, healthy lifestyle and outdoor activites and the get bick rack to create space in parking lots.
- high revenue in California and British Columbia suggest that these regions have an effective marketing strategies and stronge customer base.
- Lower revenue in Kentucky and Loir et Cher could indicate poor customers base because of lower market penetration or ineffective strategies in these areas.

### Conculsion

- The United State and Canada are the largest revenue contributors in this businss due to its high performing states making it the leading region in this business.
- United state which is the lowest performing region because the business only operates in one state.

### Recommendation
- Some underperforming regions and states needs more attention


Regions already striving should be socked up more like United State and Canada etc

![image](https://github.com/user-attachments/assets/f924b98b-2c7c-4264-8b26-4d86867fad1b)

![image](https://github.com/user-attachments/assets/c8128e08-285e-4933-acfd-9c5612026014)







