# AtliQ Hardware Business Insights 360

## Project Overview

Retailers, direct sales, and distributors are the primary channels through which AltiQ Hardware, a rapidly developing business with a global presence, sells PCs and accessories.

After launching a store in America, the company experienced unanticipated losses despite its development. These setbacks were discovered using surveys, basic Excel analysis, and intuition. Given that its rivals have strong analytics teams, AltiQ Hardware understands how critical it is to advance its analytics capabilities in order to succeed in the market.

The business has chosen to use Power BI for analytics in order to outperform rivals and facilitate data-driven decision-making. The goal of this project is to give stakeholders knowledge about supply chain, marketing, sales, and finance so that decisions at all levels are well-informed.

I followed the Codebasics PowerBi Course while working on this project.

Here is my report link - https://app.powerbi.com/groups/me/reports/c3c8fb9d-8a9a-419f-b501-ef8888cbe8dd/ac21b22e4cceead8dc30?experience=power-bi

## Key Features

* Interactive Dashboards: Visualizes key business metrics such as revenue, profit, and operational efficiency.
* Data Analysis: Uses SQL for data extraction, transformation, and aggregation.
* Dynamic Filtering: Enables users to filter data by time period, region, product category, etc.
* Predictive Insights: Implements forecasting models to anticipate future trends.

 ## Tools & Technologies

 * Power BI: For data visualization and dashboard creation.
 * SQL: For data extraction and transformation.
*  DAX (Data Analysis Expressions): For advanced calculations.
*  Excel: For initial data cleaning and preprocessing.

## Datasets:

It is essential to become familiar with the datasets before beginning any analysis. There are two tables in the datasets:

Dimension table: Static data like customer and product details.

Fact table: Transaction data.

gdb041:

* dim customer
* dim_market
* dim_product
* fact_forecast_monthly - This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and reduced cost in warehouses for storage purposes
* fact_sales_monthly - This table is more or less is same as the fact_forecast_monthly table, but the last column has the value of the sold quantity instead of the forecast value.

gdb056:

* freight_cost
* gross_price
* manufacturing_cost
* Pre_invoice_dedutions
* Post_invoice_deductions

## Importing Data and Data Modeling:

After the data was cleaned and transformed, it was imported into Power BI from MySQL and a data model was produced. However, why is data modeling so crucial to analysis?

Four steps of work will be identified if you break down the entire data analyst's job.

✅ Extracting Data ---> Cleaning Data---> ✅ Modeling Data ---> ✅ Analysis of Data
As you can see, data modeling is crucial since it establishes the framework for reporting, therefore you cannot skip the third step if you wish to get to the final step (the analysis section). The data model serves as the foundation for all visualizations, and improper modeling can impact report performance.

I used the Snowflake schema data modeling approach for this project.

![image](https://github.com/user-attachments/assets/463cfc78-7a11-46fc-a2c3-81ade2175a67)

## Power BI Dashboard Overview:

The dashboard is made up of six pages-->

### Home Page: A landing page with buttons to navigate to different pages.

![image](https://github.com/user-attachments/assets/5ccea953-d2f2-4926-abab-8a2ee3172c17)

### Finance Page: Focuses on improving financial planning, budgeting processes, and cost control. Includes Profit and Loss statements, Top and Bottom Products and Customers by Net Sales, and more.
![image](https://github.com/user-attachments/assets/8a16fe9e-758a-4554-8270-06722368c41f)

### Sales Page: Aims to increase sales revenue and market share. Features Customer performance by Net Sales, Gross Margin, Gross Margin %, and more.

![image](https://github.com/user-attachments/assets/beb68c6b-8ee1-470e-a4b3-cee42092197b)

### Marketing Page: Aims to increase brand visibility and customer engagement. Provides Segment Performance by Gross Margin% and Net Profit%, and more.

![image](https://github.com/user-attachments/assets/bf2f0c22-2a44-4d05-8798-6dbc16366f60)

### Supply Chain Page: Aims to optimize inventory management and enhance supplier relationships for cost savings. Includes details about Forecast Accuracy, Net error, and more.

![image](https://github.com/user-attachments/assets/024df9e0-5e7c-4f92-9f26-399d0565463e)

### Executive Page: Provides the top executives a summary of the organization's performance. Contains the following: Sub-region performance, Top 5 Customers and Products, Net Sales, Gross Margin%, Net Profit%, and Revenue Contribution by Channel.

![image](https://github.com/user-attachments/assets/71df351a-ab5d-4f30-bfa3-eee4e326918e)

## Skills Learned:

In this project and the Codebasics Bootcamp training, I gained knowledge of

* Power BI basics
* Calculated columns and DAX measures
* Data modeling, data cleaning, bookmarks, conditional formatting
* Using custom tooltips, creating dynamic titles, and more.

## Tools Used:

### SQL, Power BI Desktop, DAX language, DAX studio (to reduce file size), Project Charter file.

## Business Terms Learned:

Gross Sales, Gross Sales %, Gross Margin, Gross Margin %, , Pre-invoice deductions, Net Invoice Sales, Post-invoice deductions, COGS (cost of goods sold), Net sales, Net Profit, Net Profit %, YTG (year to go), YTD (year to date), Direct, Retailer, Consumer, Distributors.

## Conclusion :

Using statistics to inform decision-making, this report answers several "why" questions in a variety of settings. It is used as a tool to draw conclusions and direct activities with the ultimate goal of increasing AltiQ's profitability by making data-driven choices.
