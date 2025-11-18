# SALES PERFORMANCE ANALYSIS


## PROJECT OVERVIEW

This analysis aims to provide insights and compares sales performance across 2022,2023 and first month in 2024 to evaluate growth trends, operational efficiency, 
and shifts in customer demand.

![sales](https://github.com/user-attachments/assets/15ec4a8e-161c-4354-862a-d3509a40b9cf)

### Data Sources

Sales Data : The Primary dataset used for the analysis is the  sales_data.csv file containing the major data for the analysis.

### Tools

- MS SQL Server - Data cleaning,Data Analysis
- PowerBI - Creating Report & Dashboard 

### Data Cleaning/Preparation
In the begining stage,I performed the following task:

1. Data loading and inspection.
2. Checking and Handling missing values
3. Checking and Handling duplicates.

### Exploratory Data Analysis (EDA)

EDA involved exploring the sales data to answer the main questions, like:

- What is the overall sales trend?
- Which product category drives most sales?
- What stores are the top sellers?

  ### Data Analysis

Include some code/features worked with

```sql
select *
from sales
```

### Results/Findings

The analysis results are summarized below:
1. Sales decreased by 3% from 2022 to 2023, partly due to the epidemic:Peak sales occurred in Q3, driven by groceries and furniture, while toys had the lowest sales.   
2. Stock levels exceeded quantity ordered and sold, indicating weak demand alignment.. 
3. Store S003 performed well store while S004 led the way with the highest furniture sales.
4. Inventory (stock) level exceeded the number of quantity ordered and sold showing a weak demand alignment.
5. Unpromoted products recorded higher sales compared to promoted goods which suggest the promotional strategies are not very effective in driving demand.
6. 10% and 5% discount brought the most sales while higher discount temporarily boosted units ordered, deeper discounting reduced overall revenue.
7. Epidemic caused 85% decrease in sales.
8. North region led in sales, while clothing’s strong performance in the South and West highlights regional growth opportunities.
   
### Recommendations

Based on the analysis, I recommend the following actions:

1. Business should focus on improving promotional planning, optimizing inventory and aligning stock with real demand trend.
2. Apply smart discounting to balance sales.
3. Build business resilience to reduce the impact of external disruptions.
