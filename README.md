Sales Data Analysis - Power BI Project 1


Hey everyone, this is my first Power BI project where I analyzed some sales data from a store. I built a couple of dashboards to look at customer details and sales performance over time.
The data comes from an Excel sheet which is also included in this repo.

Files in this repository
Store+Data.xlsx: This is the raw data file containing all the transactions, store information, and order details.

over view.pbix: A Power BI dashboard that gives a high-level overview of how the business is performing.

customer details through various filters.pbix: This report focuses on customer segmentation. You can filter by different regions, categories, etc., to see specific customer info.

sales,profit,qauntity sold between dates.pbix: A specific report to track sales, profit margins, and the total quantity sold within selected date ranges.

What I did in this project
1. Data cleaning
Loaded the Store+Data.xlsx into Power BI and did some basic data cleaning in Power Query. Fixed some column types and made sure dates are properly formatted so the filters work right.

2. Data modeling
Created a basic star schema. Linked the main transaction table with calendar details and customer information so that filters can apply across all pages.

3. Key features & insights
Interactive Filters: You can filter the data by year, month, or specific regions to see how stats change.

Trend Analysis: Line charts showing how profits go up or down between different dates.

Sales Performance: Visualizations tracking overall sales metrics and quantity sold over time.

How to use it
Make sure you have Power BI Desktop installed on your computer.

Clone or download this repository.

Open any of the .pbix files to view the interactive dashboards.

If the data path breaks, you might need to change the source settings to point to the Store+Data.xlsx file on your local machine.
