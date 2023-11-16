# Online retail store sales analysis

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data sources](#data-sources)
3. [Tools](#tools)
4. [Data Cleaning/Preparation](#data-cleaningpreparation)
5. [Exploratory Data Analysis](#exploratory-data-analysis)
6. [Data Analysis](#data-analysis)
7. [Result/Findings](#resultfindings)
8. [Recommmendations](#recommmendations)
9. [Limitations](#limitations)
10. [References](#references)



## Project Overview

This data analysis aims to provide understanding on the intricacies of the data on sales perfomance of an online retail store. By analyzing various aspects of the data, we seek to understand customer trends and behavior, drive targeted marketing efforts and to enhance business strategies through comprehensive analysis to make informed decisions and generate meaningful insights and recommendations.

![Column Chart](https://github.com/trustebunu/online-store-analysis/assets/112251584/d8afafe2-9be9-457a-8681-97e3d844965a)


## Data sources

Sales Data: The primary dataset used for this analysis is the " Online Retail Data Set for Tata.xls" file, containing detailed information about each sale made by the company over a specific period of time.

## Tools

- Microsoft Excel: For Data Cleaning and Analysis [Download Here](https://www.microsoft.com/en-us/microsoft-365/excel?ocid=ORSEARCH_Bing)
- PowerBi: For creating Visualizations and reports [Download Here](https://powerbi.microsoft.com/en-us/downloads/)

## Data Cleaning/Preparation

In the initial Data preperation phase, the following tasked was performed:
1. Data loading and inspection
2. Handling missing Values/blank cells
3. Data cleaning and formaatting
4. Calculation of Revenue
   
## Exploratory Data Analysis
EDA involved exploring the online retail store data to answer key questions, such as:
- The time series of the revenue data for the year 2011 only.
- The top 10 countries which are generating the highest revenue.
- The top 10 customers by revenue.
- Insights on countries with the gretest demand of their products.
  
## Data Analysis
For the analysis the following formulas were used to:
- Include and Exclude data that did not meet a certain criteria
  - =If(D2>1,"Include","Exclude") 
  - =If(F2>0,"Include","Exclude")
- Revenue was calculated
  - =D2*F2 (Quantity * Unit price)
    
## Result/Findings
1. Sum of Revenue trended down, resulting in a 7.54% decrease between January 2011 and December 2011.﻿ Sum of Revenue started trending up on June 2011, rising by 97.73% (743,319.77) in 5 months. Sum of Revenue jumped from 760,547.01 to 1,503,866.78 during its steepest incline between June 2011 and November 2011.
2. At 285,446.34, Netherlands had the highest Sum of Revenue and was 662.89% higher than Japan, which had the lowest Sum of Revenue at 37,416.37. ﻿Sum of Revenue and total Sum of Quantity are positively correlated with each other.
3. At 280,206.02, 14646 had the highest Sum of Revenue and was 263.04% higher than 12346, which had the lowest Sum of Revenue at 77,183.60. Netherlands in Quantity > 1 include made up 21.68% of Sum of Quantity.
4. Netherlands in Quantity > 1 which was included in the analysis made up 21.68% of Sum of Quantity.﻿ Making it the country with the highest demand.
   
## Recommmendations
- Continue monitoring the revenue trends over time to identify any potential issues or opportunities. Investigate the factors contributing to the downward trend in the early part of 2011. Consider market conditions, product performance, or external factors.
- Leverage the positive trend observed from June 2011 onwards. Identify the factors that contributed to this upward trend and explore ways to sustain or accelerate it. Consider launching marketing campaigns, promotions, or new products to capitalize on the increasing demand.
- Investigate the factors that contributed to the high revenue in the Netherlands and explore whether similar strategies can be applied to other markets.
- Develop personalized strategies for high-revenue customers, such as customer 14646, to enhance their experience and potentially increase their spending. Identify the reasons behind the low revenue from customer 12346 and consider strategies to engage and retain such customers.
- Explore the positive correlation between revenue and quantity. Identify products or categories that contribute significantly to both revenue and quantity, and consider optimizing their promotion or availability.
- Consider strategies to further capitalize on this demand in Netherland as the country with the highest demand, such as bundling or promotions for multiple items.
- Establish a continuous analysis process to monitor changes in market conditions, customer behavior, and product performance. Adapt strategies based on new insights to stay ahead of the competition.

## Limitations
- I had to filter out all blank cells from the analysis and exclude all quantity less than 1 and all unit prices less than 0 because they would have affected the accuracy of my conclusions from the analysis
  
## References
1. [Google](https://www.google.com)
