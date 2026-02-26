📊 Superstore Sales & Logistics Analytics – Power BI Project

Interactive Business Intelligence dashboard analyzing sales performance, profitability drivers, and logistics efficiency using a dimensional data model (Star Schema).

📊 Dashboard Preview
🏠 Executive Overview

💰 Sales Overview

📈 Profitability Analysis

👥 Customer Analysis

📌 Business Objective

This project analyzes transactional sales and shipping data from Superstore to identify profitability drivers, operational inefficiencies, and commercial performance patterns.

The objective is to provide data-driven insights that support operational, tactical, and strategic decision-making.

📂 Dataset Overview

Source: Superstore Sales Dataset

Period: 2011 – 2013

Rows: 10,000

Columns: 18

Data Type: Transactional sales and logistics data

Key Variables

Sales

Profit

Discount

Shipping Cost

Order Date / Ship Date

Product Category & Subcategory

Customer Segment

Location (City, State, Country)

🧠 Analytical Approach

The project follows a structured Business Intelligence workflow:

Data cleaning and transformation

Data normalization

Dimensional modeling (Star Schema)

KPI development using DAX

Time-based comparative analysis (YoY)

Profitability and logistics performance evaluation

🏗 Data Model

A dimensional model was implemented to ensure scalability and analytical efficiency:

Fact Table: Sales transactions

Dimension Tables:

Products

Customers

Locations

Shipping Modes

Market Segments

Order Priorities

This structure improves performance, readability, and maintainability of the model.

📈 Key Metrics Developed (DAX)

Total Sales

Total Profit

Average Shipping Cost

Shipping Time

Total Discount

Year-over-Year Profitability

Year-over-Year Sales

Last Data Refresh Timestamp

Custom DAX measures were implemented to support advanced filtering and dynamic analysis.

📊 Business Insights

Profitability varies significantly across product categories.

Discount levels have a direct impact on margin performance.

Shipping time affects operational efficiency.

Certain regions generate high sales but lower profit margins.

Year-over-year comparison reveals growth and decline patterns.

🛠 Tools & Technologies

Microsoft Power BI

DAX

Dimensional Modeling (Star Schema)

Data Transformation

KPI Development

📂 Repository Contents

superstore-sales-logistics-dashboard.pbix → Power BI file

superstore-sales-logistics-analysis.pdf → Project documentation

Dashboard screenshots

README documentation

🚀 Future Improvements

Integration with SQL database source

Advanced forecasting integration

Profitability decomposition analysis

Margin optimization modeling

👤 Author

Juan Segundo Gnarra
Actuarial Science Student | Business Intelligence & Data Analytics
Python · SQL · Power BI
