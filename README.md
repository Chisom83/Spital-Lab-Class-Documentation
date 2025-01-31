# Project Title: Bike Racks Sales Analysis 

## Table of Content
[Overview](#overview)

[Objectives](#objectives)

[Data Source](#data-source)

[Data Visualization and Insights](#data-visualization-and-insights)

[Dashboard](#dashboard)

[Conclusion](#conclusion)

## Overview
-----
This project focuses on analyzing sales and marketing strategies for bike rack sales, with a strong emphasis on key metrics and specific business requirements. By leveraging data-driven insights, the aim is to provide well-informed, actionable strategies that enhance inventory management and boost overall sales. Through this analysis, we strive to uncover valuable trends and opportunities that will support more effective marketing and inventory decisions, ensuring sustained growth in bike rack sales.

### Objectives 

This project focuses on analyzing the following business problem 

- Revenue Distribution by Region: Analyze which countries and states generate the most revenue for bike rack sales.
and target specific regions for promotional campaigns to boost sales in high-revenue areas and address underperforming regions for improvements.
- Demographic by age group: Segment customers into age groups eg(less than 25yrs as "Youth", 24-35yrs "Young Adult", more than 35yrs "Adult" to know which age group patronize the most and tailor marketing strategies to target specific age groups and genders, optimizing product appeal for the key demographic segments.
- Product Popularity: Assess the performance of different models of bike racks (e.g., "Hitch Rack - 4-Bike") in terms of sales volume. Inorder to refine product offerings, adjust inventory, and promote best-selling items to maximize profit.
- Sales Seasonality: Analyze trends in bike rack sales across different times of the year and correlate them with external factors like holidays or cycling season, thereby planning inventory and marketing efforts according to seasonal peaks and troughs, ensuring sufficient stock during high-demand periods and reducing excess inventory during low-demand months.

### Key Performance indicator (KPIs)

- Total Revenue: The total sales generated by the store.
- Order Quantity: The total number of units sold.
- Total Profit: The earnings after deducting the cost of goods sold (COGS) and other operating expenses.

### Data Source
The dataset used for this analysis was obtained from excel and can be accessed using this link. [Download Here](https://www.microsoft.com)

### Tool used 
Microsoft Excel 
 1. For data cleaning
 2. For Analysis
 3. For visualization

### Steps followed 
 1. Data cleaning: The raw data collected was first cleaned to ensure its integrity, consistency, and quality, setting a strong foundation for effective analysis and visualization.
      - Data filtering and missing values: I began by addressing missing entries. For numerical fields such as quantity or age, I checked for outliers. If outliers were detected, I filled the blanks using the median or mode; if no outliers were present, I filled them with the average value.
       - For categorical variables like gender, country, or state, I utilized a nested IF function to logically fill in the blanks based on existing data.
       - Correcting Misspellings: I conducted a review of the dataset to identify any misspelled words or inconsistencies in text fields, replacing incorrect terms with the appropriate ones to maintain uniformity.
       - Standardizing Formats: I ensured that all relevant fields, such as Revenue, unit_price and dates, were formatted consistently to facilitate smooth analysis.
       - Sorting the Data: I organized the data according to relevant criteria, alphabetically (A to Z or Z to A) or chronologically (from oldest to newest or vice versa), to enhance readability and trend identifications.
       - Removing Duplicates: I removed duplicate records to maintain data accuracy and integrity.
       - Structuring for Analysis: Finally, I converted the cleaned data into a structured table format, making it ready for analysis using pivot tables.
2. Data analysis: In this phase, I leveraged pivot tables in Excel to summarize and analyze the data in alignment with key performance indicators (KPIs) and specific business requirements, always keeping the broader business objectives in mind. I used filters where needed to ensure the analysis was tailored and focused.
      - I created a variety of charts, including bar charts, column charts, pie charts and line charts which helped bring the data to life, making it easier to spot trends, compare metrics, and uncover insights that support strategic decision-making. I also added slicers, allowing for dynamic filtering of the data, making it easier to interact with the information and drill down into specific segments as needed.
3. Data visualization: In this phase, I crafted an interactive dashboard that brought together all the essential charts, slicers, KPIs, and the business name, arranging each element thoughtfully to ensure clarity and impact. This dashboard provided a one-stop view of the data, making it easy to spot key trends and business challenges at a glance.
     - With a clear view of the business’s pain points, I was able to provide actionable recommendations aimed at addressing these areas and drive growth. The dashboard wasn’t just a set of visuals; but a tool designed to empower decision-making, transforming data into insights and strategies that can elevate the business to the next level.

## Data Visualization and Insights
"To explore the dataset, I utilize a pivtot table to summarize the KPI and Business Requirement which was then transformed into a chart for better clarity and presentation."
### Key Performance Indicators (kPIs)
- Total Revenue
     - The store generated a total revenue of $101,720,343, representing the cumulative value of all goods sold in the store over a four-year period.
- Order Quantity
     - 1,342,327 units were solds over the same four-year period, demostrating a consistent sales performance.
- Total Profit
     - The store recorded a total profit of $44,567,951, reflecting a healthy and sustainable profit margin after all expenses.

1. #### Revenue Distribution by Region
-----
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

- California and British Columbia generate the most revenue, likely due to their strong focus on environmental sustainability, healthy lifestyle, outdoor activites and initiatives like bick rack to optimize parking spaces.
- The high revenue in most regions suggest effective marketing strategies and stronge customer base.
- Also, lower revenue in Kentucky and Loir et Cher shows poor market penetration,weaker customers bases and ineffective strategies.

### Conculsion

- The United State and Canada are the largest revenue contributors, driven by its high performing states making them key region for this business.
- United Kingdom is the lowest performing region overall because business operations are limited to a single state.

### Recommendation

- Boost Investment: More resources should be focused on high performing regions to sustain growth and further strengthen their market presence.
- Market Research: Research should be thoroughly conducted in underperforming region  to identify and address issuses hindering growth.
- Enhanced Marketing Effort: After thorough research identifying marketing strategy as the key issue, increased marketing efforts should be implemented in underperforming regions to improve visibility,enhance customer engagement and drive sales growth. 
- Strategic Expansion: The business should explore untapped markets in the United Kingdom to capitalize on their potential. 


2. ### Demographic by Age Group
-----
![image](https://github.com/user-attachments/assets/f924b98b-2c7c-4264-8b26-4d86867fad1b)

- Age Group Appeal: The product appeals primarily to adults, followed by young adults with the youth showing the less patronage.

 - Gender Insight: Male customers dominates in purchase, with a notable 13% higher patronage compared to females.


![image](https://github.com/user-attachments/assets/c8128e08-285e-4933-acfd-9c5612026014)

### Inference
#### Adults customers
- Adults purchase more due to their finacial stability and disposable income, which allows them to invest in biking accessories like bike racks.
- Adults with families are likely to purchase bike racks for transporting mutiple bikes for family outings,vacations and fitness activites.

#### Young Adults and Youth
-  Young adults purchase more than the youths due to vehicles ownership, a key prerequisite for bike racks use. 
- Youths cycle locally, lack finacial stabilityand often do not own vehicles reducing their need for bike racks.

#### Male Customers
The male gender are more engaged in outdoor activities like cycling and require bike racks for easy transportation of multiple bikes, contributing to higher patronage.

#### Conclusion 
 - Male customers dominate with 13% higher patronage, reflecting their outdoor activity interest. 
 - Adult invest the most in bike racks for pratical and family-oriented use cases, recognizing their importances for outing and vacations.
 - The youth  demographics see less value in bike racks due to budget constraintsand limited need for transporting bikes.

#### Recommendation 
Based on marketing strategy to different age group and gender:

#### Marketing for adults

- Leverage platforms like facebook, instagram, and email markerting  with captivating headlines like "Perfect for Family Cycling Tips", highlighting the product practicality and convenience for family outing and fitness activities.
- Collaborates with influencers to promote the product and offer holiday bundle deals.

#### Targeting Young Adults and Youths
- Focus more on platforms like TikTok, Instagram and YouTube to showcase the product's usability with engaging content.
- Use captivating headlines like "Affordable Solution for Cycling Adventure" and introduce flexible payment plans to attract budget-conscious buyers.

#### Strategy for Male Demographic
- Utilize sports websites, cycling communities and using  serach engine marketing like "Best Bike Rack for Mountain Bikes".
- Collaborate with male outdoor sports influencers and cycling to boost sales.

#### Strategy for Female Demographic
- Leverage platforms like pinterest, instagram and Facebook to share fitness content.
- partner with female influencers in sports and outdoor activites, using headlines like "Effortless Bike Transportation" to appeal to women.

#### General Social Media Strategy
- Develop engaging video content demonstratng how to use bike racks, addressing common concern for different demographics.
- Run targeted ads for different age group and gender, ensuring the content appeal to their specific needs.

 #### Key Takeaway
 Social media platforms are essential for reaching diverse demographics. Tailored marketing strategies with captivating content and video demonstration can effectively drive sales and customer engagement across all groups.

3. ### Product Popularity
-----
The sales performance of the various bike racks models shows a significant differences in popularity, where Hitch Rack-4-bike leads with the higest sales volume, followed by Road-250 Red,44, Road-350-W Yellow,44, Road 250 Black,52, Road-550-W-Yellow,38, Road-650 Black,52, with Road 650 Red,44 recording the lowest sales.

 ![image](https://github.com/user-attachments/assets/bc7ab443-2f45-44e4-864c-8858d5b13638)

 ### Inference
- Hitch Rack 4 bike appals more to customers because it has the capacity to carry mutiple bikes, making it ideal for families who need solution for transporting their bikes effeciently.

#### Conclusion
- Hitch Rack 4 bike is the most in demand and best selling product,generating the highest revenue and profit for the business.
- The significant gap in sales volume between Hitch Rack 4 bike and other models shows its popularity among customers.

#### Recommendation
- Increase inventory and investment in Hitch Rack 4 bike to capitalize on its strong demand and maximize revenue generation while other bike models should be reduced in its inventory.
- Hitch rack 4 bike should be promoted more while exploring other strategy to boost the visibility and sales of other product.
- Indepth reserach should be conducted to understand why Hitch rack 4 bike outperforms other bike rack models then use the insight as a guide to future product investment and discountinue underperforming models.

#### Key Takeaway
Hitch Rack 4 bike is the business most popular and profitable product and focusing more on inventory management and strategy that will derive sales and growth increase its popularity the more and also trying out new ways to improve sales and visibility of other models.

4. ### Sales Seasonality
------
The sales of bike racks vary across state and years, but the overall trend highlights June as the month with the higest sales, followed by May, March, September, July and other months while Apirl records the lowest sales. 
A line chart was used to analyze sale trend over the months, highlighting peak and off-peak periods.

#### Inference 
- High sales in spring and summer alings with holiday and favourable weather, which encourages outdoor activites like cycling.
- The trends reveal that external factors such as weather and holidays strongly influence purchasing behaviour.

#### Conclusion 
- Spring and summer, particularly June and May are the peak sales periods due to holidays and optimal weather condition for cycling.
- Despict slight variation in regions and years, the pattern consistently identifies June and May as the top performing months.

#### Recommendation
#### Inventory Management
- Peak Seasons: Increase inventory during high demand month to meet customers needs and avoid lost sales.
- Low Seasons: Reduce inventory during low demand month to avoid overstocking and loss.
#### Marketing Strategy
- organizing promotional campaing during holidays and cycling season to boost sales.
#### Key Takeaway
Understanding sales seasonality is crucial for inventory planning and markerting strategies. By preparing for peak periods and optimizing inventory throughout the year business can enhance profitability and customer satisfaction. 

## Dashboard
This interactive dashboard consolidates all the visuals and enabled effective analysis of the business pain point.

## Conclusion
This projects analyze bike rack sales data that uncover key insights and provide actionable recommendations to address business problem. The analysis help in data-driven decisions-making, fostering business growth and operational efficiency.



 



 

 



