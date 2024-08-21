# 2020-Financial-Data-Analysis
I conducted an in-depth financial data analysis for an **online education provider**, analyzing data across various dimensions including regions, time periods (months and weeks), clients, and product categories. This comprehensive analysis focused on sales and revenue, breaking down performance by region, month, office, product, and category. 

My work provided **critical insights** into regional sales trends, seasonal variations, and product performance, enabling the company to make informed decisions about resource allocation, marketing strategies, and product development. The analysis also identified key areas for potential growth and optimization, contributing to the company's overall financial strategy.

# KPI
**Regional Sales Contribution**: Approximately 80% of total revenue was consistently generated from the Liverpool office, leading to strategic investment in that area. The two new offices in Manchester and Nottingham contributed 2.32% of overall sales.

**Seasonality**: Quarters 2 and 3 accounted for 86% of overall sales in 2020. For instance, in July alone, $2,215,508.64 in sales were registered, highlighting significant seasonal trends.

**Client Profile**: A substantial portion of clients came from the Adults and Juniors sections, while other categories, such as Groups and Executive, contributed only 0.13% of overall sales.

**New Offices' Sales Contribution**: Out of the total generated revenue of $6.62 million, the two new offices contributed $162,430 in sales, representing 2.32% of the overall sales.

## Table of contents
 - [Project Overview](#project-overview)
 - [Data Source](#data-source)
 - [Tools Used](#tools-used)
 - [Data cleaning](#data-cleaning)
 - [Exploratory data analysis](#exploratory-data-analysis)
 - [Hypothesis Testing](#hypothesis-testing)
 - [Data Analysis](#data-analysis)
 - [Findings](#findings)
 - [Power BI Visualization](#power-bi-visualization)
 - [Recommendations](#recommendations)
 - [Limitations](#limitations)
 - [References](#references)
 - [Presentation Video](#presentation-video)

### [Project Overview]()
This project involved a comprehensive financial analysis for an online education provider, focusing on sales performance across regions, time periods, and client segments. The analysis provided key insights into revenue distribution, seasonal trends, and the impact of new offices in Manchester and Nottingham. 

These insights supported strategic decisions, optimizing resource allocation, marketing efforts, and product offerings, ultimately contributing to improved financial performance and business growth.

### [Data Source]()
The data is obtained from the educational provider task analysis. 

### [Tools Used]()
- Excel: For initial data exploration and summary statistics
- Google BigQuery: Primary data cleaning
- SQL: For data cleaning and transformation
- Panda: For data cleaning, inspection and analysis
- Power BI: Visualization, DAX, measures

### [Data cleaning]()
To clean the data I performed the following tasks:
- Reading the SCHEMA, data dictionary and understanding the details of the data
- Handling null values and understanding the columns
- Handling missing values and duplicates
- Data cleaning, formatting, and also dates and numbers adjustment

 ### [Exploratory Data analysis]()
 In this analysis, I explored key questions to understand the financial performance and trends for the online education provider:

- How did sales performance vary across different regions? Investigated revenue distribution and identified high-performing regions.
- What were the seasonal trends in sales? Analyzed sales data to uncover significant seasonal patterns and peaks.
- How did the new offices contribute to overall revenue? Assessed the sales contributions of the new offices in Manchester and Nottingham.
- What were the client segments, and how did they impact sales? Examined client profiles and their contributions to overall sales.
- How did sales figures compare across different product categories? Compared revenue performance across various product categories to identify top performers.
- What were the trends in revenue growth over time? Evaluated how revenue growth evolved throughout the year.
- Were there any anomalies or outliers in the sales data? Identified and analyzed unusual data points or patterns that could impact the analysis.

### [Hypothesis Testing]()
- **Regional Sales Discrepancies**: Sales performance was notably higher in the Liverpool region compared to the new offices in Manchester and Nottingham.
- **Seasonal Revenue Trends**: Sales peaked during Quarters 2 and 3, with a significant decline in other quarters, indicating strong seasonal patterns.
- **Client Segment Contribution**: The Adults and Juniors client segments contributed the majority of the overall sales, while Groups and Executive segments had minimal impact.
- **New Office Revenue Impact**: The new offices in Manchester and Nottingham contributed a small percentage of overall revenue, with their impact being relatively minor compared to established regions.
- **Product Category Performance**: Certain product categories consistently outperformed others in terms of revenue, suggesting a preference for specific products.
- **Revenue Trends Over Time**: There were observable trends in revenue growth over the year, with certain months showing significant increases.
- **Outlier Detection**: Some sales data points were identified as outliers, which could impact overall trends and require further investigation.

### [Data Analysis]()
For data analysis and cleaning I used SQL. 

### [Findings]()
1. **Regional Sales Discrepancies**: The Liverpool region consistently outperformed the new offices in Manchester and Nottingham in terms of sales revenue. This suggests that Liverpool is a more lucrative market and may warrant further investment and resource allocation compared to the newer locations.

2. **Seasonal Revenue Trends**: Sales data revealed strong seasonal trends, with significant revenue peaks in Quarters 2 and 3. This indicates that certain times of the year, likely influenced by factors such as promotions or market demand, drive higher sales. Planning and strategy should align with these peak periods to maximize revenue.

3. **Client Segment Contribution**: The Adults and Juniors client segments were responsible for the majority of sales, whereas Groups and Executive segments contributed minimally. This highlights the importance of focusing marketing and sales efforts on the primary client segments that drive most of the revenue.

4. **New Office Revenue Impact**: The new offices in Manchester and Nottingham collectively contributed only a small fraction of total revenue. Their limited impact suggests that these locations are still in the early stages of establishing their market presence and may need targeted strategies to enhance their contribution to overall sales.

5. **Product Category Performance**: Analysis showed that certain product categories consistently generated higher revenue than others. This suggests a preference for specific products, indicating that focusing on these high-performing categories could optimize sales performance and inventory management.

6. **Revenue Trends Over Time**: There were noticeable trends in revenue growth throughout the year, with specific months experiencing significant increases. Understanding these trends can help in forecasting and planning for future periods, ensuring resources and marketing efforts are aligned with expected revenue patterns.

7. **Outlier Detection**: Several outlier data points were identified in the sales data. These outliers could be due to exceptional events or anomalies and may affect overall trends. Further investigation is needed to understand these anomalies and determine their impact on the financial analysis.

### [Power BI Visualization]()
<img width="1467" alt="1" src="https://github.com/user-attachments/assets/29c41c32-f5ea-4254-aeef-1edd76e7515d">
<img width="1470" alt="2" src="https://github.com/user-attachments/assets/5ef917e8-7ef4-4d25-9a13-58d3ca4373ef">
<img width="1470" alt="3" src="https://github.com/user-attachments/assets/56231c60-a5d1-4fb5-a016-35cc3ae36532">
<img width="1468" alt="4" src="https://github.com/user-attachments/assets/62192333-a4cc-452f-98a5-be63c58dbaae">
<img width="1469" alt="5" src="https://github.com/user-attachments/assets/63331508-47b7-4ed1-8c05-47d7376f5d98">

### [Recommendations]()
- **Increase Investment in Liverpool**: Given the consistently high sales performance in Liverpool, consider increasing marketing efforts and resource allocation in this region to further capitalize on its strong market presence.
- **Optimize Strategies for Peak Quarters**: To maximize revenue, align business strategies with the seasonal peaks observed in Quarters 2 and 3. Plan promotions, inventory adjustments, and marketing campaigns to leverage these high-demand periods.
- **Focus on High-Performing Client Segments**: Concentrate marketing and sales strategies on the Adults and Juniors segments, as these groups generate the majority of sales. Develop targeted campaigns and personalized offers to further engage these valuable clients.
- **Enhance Market Penetration in New Offices**: Implement targeted strategies to boost sales performance in the new offices in Manchester and Nottingham. Consider localized marketing efforts, partnerships, or special promotions to increase their market share and revenue contribution.
- **Prioritize High-Performing Product Categories**: Focus on the product categories that consistently generate higher revenue. Streamline inventory management and marketing efforts to promote these top-performing products, and consider expanding the product range based on customer preferences.
- **Plan for Revenue Trends**: Use the observed revenue trends to forecast future performance and adjust business planning. Ensure that resources, staffing, and marketing efforts are aligned with the expected revenue patterns to optimize financial outcomes.
- **Investigate and Address Outliers**: Perform further analysis on the identified outliers to understand their causes and impacts. Determine if these anomalies are due to exceptional circumstances or errors, and adjust strategies accordingly to mitigate any potential negative effects on overall trends.

### [Limitations]()
- **Regional Variability**: The financial performance of the new offices in Manchester and Nottingham may be influenced by local market conditions and competition, which are not fully captured in the analysis. The findings may not be generalizable to other regions or contexts.
- **Seasonal Factors**: While seasonal trends were identified, other external factors such as economic conditions, market trends, or changes in consumer behavior were not accounted for. These factors could also influence sales performance and should be considered in future analyses.
- **Outlier Impact**: The presence of outliers in the data may skew the overall findings and impact the accuracy of trend analysis. Further investigation is needed to determine the causes of these outliers and their influence on the results.
- **Segmentation Limitations**: The analysis of client segments and product categories is based on the available segmentation data, which may not capture all relevant distinctions. This could limit the depth of insights into customer behavior and product performance.
- **Time Period Constraints**: The analysis covers a specific time period, which may not fully reflect long-term trends or variations. Seasonal patterns and business cycles outside this period were not included in the scope of this analysis.
- **Assumptions in Analysis**: The findings are based on certain assumptions about the data and the business environment. Any changes in these assumptions or unaccounted variables could affect the validity of the conclusions.
- **No Experimental Data**: The analysis was performed using historical data without experimental or control data. This limits the ability to establish causal relationships or test specific interventions.

  ### [References]()
No reference materials were used in this analysis

### [Presentation Video]()
[Watch my presentation video for this analysis](https://drive.google.com/file/d/149gPzWwHaLFPqMYe4cgAnY1ethSFuxdT/view?usp=drive_link) to see the detailed analysis and insights!
