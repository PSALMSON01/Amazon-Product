# Amazon-Product
RetailTech Insights is a company that provides e-commerce analytics solutions to sellers on platforms like Amazon

**Project Topic: Amazon Product Review Analysis**

**Project Overview**
This project analyzes Amazon product reviews by combining high ratings with customer feedback, using sentiment analysis and visual exploration. It uncovers patterns in customer satisfaction, highlights common issues across products and categories, and compares how sentiment aligns with numerical ratings. The goal is to gain a deeper understanding of the customer experience beyond just the star ratings.

**Project Objectives:**
Examine the relationship between customer sentiment and star ratings to determine where they align or diverge across different products and categories.
Identify products that generate the most divided opinions, as well as those with consistently positive or negative feedback trends.
Develop interactive visualizations that present key insights and enable users to explore data by filtering based on ratings.
Generate actionable insights and practical recommendations to support product enhancement, marketing strategies, and customer service initiatives—grounded in authentic user feedback.

**Data Set**
The dataset, provided for a training project, contains Amazon product reviews across multiple categories. It includes key fields like ratings, customer IDs, usernames, review text, and product identifiers. Structured to reflect real-world e-commerce data, it supports hands-on learning in sentiment analysis, data visualization, and customer behavior insights.

**Technologies Employed**

**Tools Utilized for Data Analysis, Text Processing, and Visualization**
The following tools were employed to efficiently analyze data, process text, and enhance visual representation:

**Microsoft Excel**
Excel: Used for quick data inspection, filtering, and basic formatting to gain an initial understanding of the dataset.
Power Query: Essential for data transformation and cleansing tasks such as filtering, splitting columns, removing duplicates, and shaping the dataset for more advanced analysis.

Pivot Tables: Employed to quickly summarize data, including customer ratings, category counts, and sentiment groupings. These summaries helped inform the structure of the final dashboard.

Pivot Charts: Visual tools like clustered column charts, doughnut charts, and pie charts were used to represent key metrics such as rating distribution, review counts, and category trends. These visuals supported early insights during the exploratory phase prior to creating more advanced dashboards.

Excel Dashboards: Designed to provide interactivity and a clear overview by integrating slicers, charts, and KPI cards. These dashboards effectively presented product performance and sentiment insights in an intuitive format.

**Data Cleaning And Preparation**
Prior to analysis, the dataset was carefully cleaned and transformed to ensure it was accurate, consistent, and compatible with tools such as Microsoft Excel.

Filtering: Removed irrelevant entries and duplicate values in the Product and Category columns to reduce unnecessary characters and ensure uniqueness.

Text Cleaning: Applied the =CLEANTRIM function to eliminate special characters and extra spaces, and used the =PROPER function to standardize text casing—essential for accurate sentiment and keyword analysis.

Column Elimination: Removed non-essential columns that did not contribute to the analysis.

New Column Creation: Introduced calculated fields such as Price Bucket, Potential Revenue, High Discount, Reviews, and Rating Score to provide a foundation for deeper insights and analytical comparisons.

Data Formatting: Assigned appropriate data types and formatting to ensure consistency and compatibility across the dataset.

**Data Review & Understanding**

Data Review was conducted to know the behaviour of the dataset before carrying out proper Analysis and visualization

1. What is the average discount percentage by product category?

2. How many products are listed under each category?

3. What is the total number of reviews per category?

4. Which products have the highest average ratings?

5. What is the average actual price vs the discounted price by category?

6. Which products have the highest number of reviews?

7. How many products have a discount of 50% or more?

8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)?

9. What is the total potential revenue (actual_price × rating_count) by category?

**INSIGHT FROM THE REVIEW**

Most products received high customer ratings.

Significant discounts tend to boost sales volume.

The number of reviews varies greatly across products.

Products with lower ratings generally show reduced customer engagement.

Certain low-priced products generate substantial revenue.

**OBSERVATION**

Most products cluster within a tight rating range of 4.0 to 4.5

Products with higher review counts generally correspond to greater potential revenue.

Items with lower ratings have noticeably fewer reviews, limiting their overall impact.

Lower-priced products can still perform strongly when sales volume is high.

**Conclusion**

The analysis reveals that most products maintain consistently high ratings within a narrow range, indicating general customer satisfaction. Products that garner more reviews tend to generate higher potential revenue, highlighting the importance of customer engagement. Conversely, lower-rated items attract fewer reviews, which diminishes their market influence. Additionally, lower-priced products can achieve strong performance when supported by high sales volume, underscoring the role of pricing strategy in driving success.

