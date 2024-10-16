# Pivot
This is an assignment given on Pivot Chart and documentation of the work done.

## Outline
## [Project Overview](#project-overview)
## [Data Sources](#data-sources)
## [Tools Used](#tools-used)
## [Data Cleaning and Preparation](#data-cleaning-and-preparation)
## [Exploratory Data Analysis](#exploratory-data-analysis)
## [Data Analysis](#data-analysis)
## [Results/Insights](#Results/Insights)


### Project Overview
---
This is an assignment given based on Pivot data, where I was tasked to;

1. Create a 10-15 visual report from the data shared for the pivot data

2. Document your step by step analysis from the Data given.

3. Tell a compelling story sharing business insight to drive a successful business decisions

### Data Sources
---
The data used for this assignment was shared by the facilator for SkilHarvest Data Analysis class.
Dataset has 10 columns and 30,800 rows

### Tools Used
---
- MS Excel [Download Here](https://www.microsoft.com)
    1. This is the major tool used for analysis
 
### Data Cleaning and Preparation
---
The data shared had already been cleaned.
I expanded columns and checked for duplicates.

### Exploratory Data Analysis
---
EDA Checklist:
1. Summary Statistics: Understand basic metrics (sum, max, count).
2. Visualizations: Use charts (bar charts, area graphs, pie charts, line graphs to visually explore data.
3. Categorical Data: Summarize and visualize categorical variables.

### Data Analysis
---
Excel Function (IF Function)
This was used to calculate the Sales Category
```
=IF(J4<=20,"LOW",IF(J4<=50,"MEDIUM",IF(J4>50,"HIGH")))
```
### Results/Insights
---
From the data shared and the charts created;
1. The sum of revenue in the different regions, stores and market was analysed which amounted to 73.03B

2. Profit generation shows that the year 2014 had better sales compared to 2015.
- Total Sales in 2014: 48.46B
- Total Sales in 2015: 28.57B

The low sales in 2015 was due to the fact that the revenue was only generated from Jan to June,
whereas 2014 had revenue which ran through the entire months of the year.

4. line of businesses;
   - Service Plan
   - Printer Sales
   - Parts
   - Copier Sale

6. Category of Days;
   - Work day
   - Local holiday
   - Observance
   - Season
   - Public holiday
  
7. The total number of stores is 132
8. There were 9 different models

#### Business Decisions
---
1. Unique Regional Strategies: A region-specific strategy can be adopted. High-performing regions (e.g., North East) made great revenue, while regions (e.g., the North-Central) had low revenue. This strategy can enable all regions to be equally focsed on.

2. Capitalizing on the Day Category: From the charts, we analysed that the Work day had the highest number markets and the Local holiday had the least, this implies the work day will have higher revenue.

#### Key Points:
1. Understanding regional performance and adapting strategies to specific stores can unlock hidden growth potential.
2. Understanding the seasons i.e the day category can drive customer engagement and maximize revenue.

#### Problem Statement
Revenue generation is a core part of any business. This generation is influenced by a number of factors, which include the regions, markets, stores, etc. There have been issues about revenue generation in the company by region, where certain regions were generating income than others. This analysis provides insight to solve the issue with respect to day category and its effect on the revenue. 

#### Recommendations
By leveraging data on regions, markets, stores, day category, we can see the result in the charts.
Understanding the data can lead to higher revenue generation across regions.


