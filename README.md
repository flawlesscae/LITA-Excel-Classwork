 # Sales Analysis using Microsoft Excel
## Outline
[Overview](#overview)

[Data Collected](#data-collected)

[Objectives](#objectives)

[Key Metrics](#key-metrics)

[Tools](#tools)

[Steps](#steps)

[Data Analysis](#data-analysis)

[Visualization](#visualization)

[Inference](#inference)

### Overview
---
In this project, the data collected from various regions, markets, stores and transaction categories over several months and years is analyzed to help the board of directors in understanding revenue trends and sales performances across all regions.  

### Data Collected 
---
The data set contains the following key details:
1. **Region**: The geographical locations of the stores.
2. **Market**: Specific categories within a region.
3. **Store**: Each store from which data was collected.
4. **Trade Date**: The dates on which specific item sales were made.
5. **Fiscal Period**: The time between the start and end of the trade date.
6. **Model**: The specific group of products sold.
7. **Line of Business (LOB)**: Whether it be a retail or wholesale line of business.
8. **Day**: The exact day a sales transaction took place.
9. **Category**: Product categories
10. **Revenue**: The monetary values generated from sales from all stores.
11. **Units Sold**: Quantity of items sold per transaction.
12. **Transaction Category**: Whether the sales were made online or onsite.
    
### Objectives
---
The objectives of this report is to find:
1. Total revenue generated from each region.
2. The region with the highest sales.
3. Average sales per region.

### Key Metrics
---
Listed below are the key metrics used to meet the set objectives;
1. Revenue
2. Region
3. Units sold
4. Market

### Tools
---
The tools used include:
- Microsoft Excel for 
  1. Cleaning
  2. Analysis (using pivot tables) and 
  3. Visualization (using charts)

### Steps
---
The following actions were the first steps taken to prepare our data set:
1. Data loading and Inspection
2. Data Cleaning and Formatting

### Exploratory Data Analysis 
---
EDA involves exploring the data set to answer key questions such as:
- Overall sales trend.
- Which stores are the generating the most revenue.
- What regions have customers with the most purchasing power.

### Data Analysis
---
Listed below are basic formulas/codes/queries and even DAX (data analysis expressions) used during analysis; 
```
Autosum of revenue
Autosum of units sold
Average Revenue = Total Revenue / Units Sold
```
  
## Visualization
---
### 1. Revenue by Region 

![LITA Revenue](https://github.com/user-attachments/assets/e1a06135-b89f-4b9d-8783-2bdb07190186)

![LITA Revenue Chart](https://github.com/user-attachments/assets/6ba90490-7fbe-4755-bf87-1f8afde296ab)



### 2. Sum of Units Sold by Region

![LITA Sums of Units Sold](https://github.com/user-attachments/assets/bb9a3805-b418-4bf5-bdf8-649a0dc508b3)

![LITA Sums of Units Sold Chart](https://github.com/user-attachments/assets/57439113-35c6-4a1e-adf9-68a4116cfe9f)



### 3. Top 5 Markets by Revenue

![LITA Top 5](https://github.com/user-attachments/assets/b8136dae-b22d-4223-a13a-7413ea27ae40)

![LITA Top 5 Chart](https://github.com/user-attachments/assets/9919d89e-2f7c-4b99-9817-0577dc0d674f)


## Inference
---
### 1. Revenue by Region
**(a). Overall Revenue:**
- The total revenue across all regions is significantly exceeding 73 billion.
- There is a substantial variation in the revenue generates across regions.
  
**(b). Regional Performance:**
- The North-East region generated the highest revenue, followed by the South-West and South-South regions.
- The region that generated the lowest revenue of 6,489,332,640bn is the North-Central, the North-West region made a slightly higher revenue (9,386,346,720bn) than the North-Central region.

**(c). Potential Insights:**

**Market Potential:** 
- Regions with higher revenue might have untapepd market potential for further growth.
- More marketing should be done in those areas by way of e.g introducing categories of incentives for loyal/returning and new customers.

**Operational Efficiency**
- Further analysis should be done to identify areas for improvement in operational efficiency for regions generating lower revenue.
- Marketing strategies targeted at bringing in and retaining new customers should be employed.

**Geographical Factors**
- Analysis on how certain factors such as population density, economic activity, and infrastructure could influence regional revenue disparities should be carried out.
- Strategies on how to leverage the above to the company's advantage should be developed and implemented.

### 2. Sum of Units Sold by Region
**(a). Overall Sales Performance:**
- The total units sold across all regions is 786,678. This indicates a significant sales volume.
- There is a variation in sales performance across regions, with North East leading in sales followed by South West and South South.

**(b). Regional Performance:**
- **North East:** This region boasts the highest sales figures, likely indicating a strong market presence, effective marketing strategies, or a combination of both.
- **South West and South South:** These regions show consistent performance, suggesting a stable market and potentially a loyal customer base.
- **North Central and North West:** These regions have the lowest sales figures as compared to other regions. This could be due to various factors such as economic conditions, infrastructure, or competitive landscape in those regions.

**(c). Potential Insights:**
- **Markt Expansions:** The North East region could be a potential target for expanding sales efforts in other regions.
- **Marketing Optimization:** Analyzing the marketing strategies of the North East region could provide insights for improving sales in other regions.
- **Regional Analysis:** A deeper analysis of the factors influencing sales in each region could provide valuable insights for future strategies.
- **Customer Segmentation:** Identifying specific customer segments within each region could help tailor marketing efforts and improve sales.

**(d). Limitations:**
- Without additional context, like time period, product type, or competitive landscape, it is difficult to draw definitive conclusions about the underlying causes of low sales performances in the regions with the lowest revenues.
- A more comprehensive analysis would require additional data points, such as market share, customer demographics, and economic indicators.

**(e). Recommendations:**
- Conduct a detailed analysis of each region's market dynamics and competitive landscape.
- Implement targeted marketing strategies for each region based on their specific needs and preferences.
- Monitor sales trends regularly to identify potential issues and opportunities.
- Invest in market research to gain deeper insights into customer behaviour and preferences. 

### 3. Top 5 Markets by Revenue
**(a). Overall Revenue:**
- The overall revenue across the 5 top markets exceeds 22bn which is about 30% of the total revenue generated across board.
- There is a clear variation in revenue generation across these markets which could have been influenced by factors such as economic conditions, infrastructure etc.

**(b). Market Performance:**
- Ekiti has the highest revenue, followed by Abia and Bayelsa.
- Akwa Ibom and Kogi have the lowest revenue amongst the 5.

**(c). Potential Insights:**
- **Market Potential:** Ekiti, Abia and Bayelsa seem to have significant market potential.
- **Competitive Landscape:** Understanding the competitive landscape in each market can help identify opportunities and challenges.
- **Marketing Strategy:** Tailoring marketing strategies to specific markets could optimize resource allocation and increase revenue.
- **Geographical Factors:** Factors like population density, economic activity, and infrastructure could influence market revenue.

**(d). Limitations:**
- Without additional context, like time period, product type, or competitive landscape, it is difficult to draw definitive conclusions about the underlying causes for revenue generation patterns across markets.
- A more comprehensive analysis would require additional data points, such as market share, customer demographics, and economic indicators.

 **(e) Recommendations:**
 - Conduct a detailed analysis of each market's dynamics and competitive landscape.
 - Implement targeted marketing strategies for each market based on their specific needs and preferences.
 - Monitor revenue trends regularly to identify potential issues and opportunities.
 - Invest in market research to gain deeper insights into customer behavior and preferences.


### Link for tools download
---
1. Microsoft Excel [Download Microsoft Excel Here](https://www.microsoft.com)


   


