📊 Executive Sales & Business Performance Dashboard
📌 Project Overview

This project presents an End-to-End Business Intelligence Dashboard built using Power BI and Excel.

The dashboard provides insights into:

Sales Performance

Profit Analysis

Customer Segmentation

Return Analysis

Target vs Actual Performance

📂 Dataset Description

This project uses four datasets:

1️⃣ Sales Dataset

Columns:

Order ID – Unique identifier for each order

Customer ID – Customer reference key

Order Date – Date of transaction

Product ID – Product reference

Category – Product category

Region – Sales region

Sales – Revenue generated

Cost – Product cost

Quantity – Units sold

📌 Purpose:
Acts as the Fact Table containing transactional data.

2️⃣ Customer Dataset

Columns:

Customer ID – Unique identifier

Gender – Male/Female

Age – Customer age

Payment Method – Mode of payment

📌 Purpose:
Dimension table used for customer segmentation analysis.

3️⃣ Returns Dataset

Columns:

Return ID – Unique return reference

Order ID – Associated sales order

Return Date – Date of return

Return Reason – Reason for return

📌 Purpose:
Used to calculate return rate and analyze quality issues.

4️⃣ Target Dataset

Columns:

Target ID – Unique reference

Year – Target year

Month – Target month

Region – Target region

Target Sales – Expected revenue

Target Profit – Expected profit

📌 Purpose:
Used to compare actual vs planned performance.

🏗 Data Modeling

The project follows a Star Schema:

Fact Table: Sales

Dimension Tables: Customers, Date Table

Supporting Tables: Returns, Targets

Relationships created using:

Customer ID

Order ID

Region

Date

📈 Key KPIs Created

Total Sales

Total Profit

Total Quantity

Return Rate %

Sales Achievement %

Target vs Actual Comparison

🛠 Tools Used

Power BI Desktop

Excel

DAX

Power Query

📊 Dashboard Features

Interactive slicers (Year, Month, Region, Gender, Category)

Monthly Sales Trend

Regional Performance

Customer Segmentation

Return Analysis

Target Achievement Analysis

💡 Business Insights

Identified top performing regions

Analyzed customer demographics

Measured return rate trends

Compared actual sales vs targets
