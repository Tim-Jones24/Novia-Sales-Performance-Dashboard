# Novia Sales Performance Dashboard
A comprehensive sales Analysis using  Power Pivot in Excel: A Data-Driven Approach to Revenue & Profit Optimization.






## Sales Performance Analysis and KPI Dashboard Using Power Pivot in Excel

#### Project Overview

This project provides a comprehensive sales analysis dashboard using Power Pivot in Excel, designed to help businesses monitor key performance indicators (KPIs)
and drive strategic decisions. The dataset,**Novia Sales**, includes financial, product, segment, location, and sales channel data, structured into start schema model.

#### Key Objectives:

*  Build an interactive Power Pivot model to analyze sales trends.
*  Use DAX Calculations to derive finacial insights such as profit margin, revenue, profit and profit categories.
*  Create dynamic KPIs (e.g., total revenue, average profit, top- performing products, and customer segments)
*  Use Excel cube functions and SL Functions to enhance dashboard interactivity.
*  Provide business recommendations to optimize sales, revenue amd profitability.

#### Data Model ( Star Schema Design)
The data model follows a start schema with a fact table (Financials) and multiple dimension tables:

1. **Financials**: Sales transactions with cost, revenue, and quality details.
2. **Segments**: Customer Segment classifications.
3. **Products**: Product details.
4. **Sales Channel**: Different sales chanels.
5. **Locations**: Sales performance by state.
6. **Calendar**: Derived time-based table for dynamic reporting.

#### Calculated Columns (DAX in Power Pivot)
To enrich the dataset, the following calculated columns were created:

* **Profit Margin** = (Profit / Revenue) * 100
* **Revenue** = Quantity Sold * Price
* **Expenses** = Quantity * Cost of Sales
* **Profit** = Revenue - Expenses
* **Profit Category**: High or Low, based on comparison with the average profit.

#### Busines Questions Answered
* **Top 5 products by revenue**: identifies best-selling products.
* **Most profitable customer segment**: Helps optimize marketing efforts.
* **Revenue by Sales Channel**: Compares revenue performance across channels.
* **Monthly revenue trends**: Tracks seasonal variations.
* **Top 5 states by profit**: Determines key geographic markets.

#### KPIs Monitored

* Total Revenue
* Average Profit
* Total Quantity Sold
* Total Expenses
* Total Products
* Total Locations
* Total Sales Channels
* Total Segments

#### Tools & Technologies Used

* **Microsoft Excel** (Power Pivot, Pivot Tables, Cube & SL Functions)
* **DAX** (Data Analysis Expressions) for calculated columns and measures.
* **Data Modelling** (Star Schema Design)
* **Data Visualization in Excel Dashboards**

#### Recommendations to Improve Sales & Revenue

* Replicate Q3 strategies to maintain peak sales momentum.
* Focus marketing on top-performing products to maximize revenue.
* Expand operations in profitable states and optimize sales channels.
* Introduce seasonal promotions and loyality programs to increase customer retention.
* Monitor KPIs in real time using the dashboard for data-driven decision making.
* Implement predictive modelling as sales grow to forecast future sales and proactively adjust inevntory marketing and pricing startegies.

#### Conclusion

This project demonstrates how Power Pivot in Excel can be used for advanced business intelligence, enabling companies to analyze sales performance efficiently. By leveraging DAX calculations, Pivot Tables, and KPI tracking, businesses can gain actionable insights and drive revenue growth.

#### Datasaet Credit
Novia Sales Dataset: Provided by Michael Ogbeide
LinkedIn: https://www.linkedin.com/in/michael-ogbeide/
