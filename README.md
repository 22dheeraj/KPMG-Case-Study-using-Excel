📊 KPMG Data Analysis Using Excel

Data Management and Analysis with MS Excel

📖 Project Overview

This project focuses on analyzing customer demographics, transactions, and new customer data from KPMG to generate insights into business performance and customer behavior.

The project involves data cleaning, customer segmentation, transaction analysis, new customer insights, Customer Lifetime Value (CLV) analysis, and executive recommendations using Microsoft Excel.

🎯 Business Objective

KPMG seeks to:

Improve customer understanding through segmentation

Detect transactional patterns and sales trends

Identify high-value customers via CLV analysis

Assess new customer potential for business expansion

Provide data-driven recommendations for strategy

📂 Dataset & Description

1️⃣ Customer Address Dataset

Contains information about customer addresses and property valuation.

| Column              | Description                         |
| ------------------- | ----------------------------------- |
| customer\_id        | Unique ID for each customer         |
| address             | Customer street address             |
| postcode            | Postal code                         |
| state               | State of residence (e.g., NSW, QLD) |
| country             | Country (Australia for all entries) |
| property\_valuation | Property valuation score            |

2️⃣ Customer Demographic Dataset

Demographic details including job, wealth segment, and personal info.

| Column                                   | Description                                 |
| ---------------------------------------- | ------------------------------------------- |
| customer\_id                             | Unique ID                                   |
| first\_name, last\_name                  | Customer’s name                             |
| gender                                   | Gender of customer                          |
| past\_3\_years\_bike\_related\_purchases | Bike-related purchases in last 3 years      |
| DOB                                      | Date of birth                               |
| job\_title                               | Job title                                   |
| job\_industry\_category                  | Job industry                                |
| wealth\_segment                          | Wealth classification (e.g., Mass Customer) |
| deceased\_indicator                      | Y/N                                         |
| default                                  | Data quality flag                           |
| owns\_car                                | Yes/No                                      |
| tenure                                   | Customer tenure                             |

3️⃣ Transactions Dataset

Details of customer purchases.

| Column                     | Description                       |
| -------------------------- | --------------------------------- |
| transaction\_id            | Transaction ID                    |
| product\_id                | Product ID                        |
| customer\_id               | Customer ID                       |
| transaction\_date          | Date of transaction               |
| online\_order              | Online purchase flag (TRUE/FALSE) |
| order\_status              | Status (e.g., Approved)           |
| brand                      | Product brand                     |
| product\_line              | Product category                  |
| product\_class             | Class (e.g., medium)              |
| product\_size              | Size                              |
| list\_price                | Price                             |
| standard\_cost             | Cost                              |
| product\_first\_sold\_date | First sold date                   |

4️⃣ New Customer List Dataset

Potential new customer details.

| Column                                   | Description              |
| ---------------------------------------- | ------------------------ |
| first\_name, last\_name                  | Name                     |
| gender                                   | Gender                   |
| past\_3\_years\_bike\_related\_purchases | Past purchases           |
| DOB                                      | Date of birth            |
| job\_title, job\_industry\_category      | Occupation details       |
| wealth\_segment                          | Wealth classification    |
| deceased\_indicator                      | Y/N                      |
| owns\_car                                | Yes/No                   |
| tenure                                   | Tenure                   |
| address, postcode, state, country        | Location                 |
| property\_valuation                      | Property value           |
| Rank                                     | Rank of customer         |
| Value                                    | Potential customer value |

📝 Tasks

| **Task**                               | **Objective**                                                                 
| -------------------------------------- | -----------------------------------------------------------------------------
| 1. Data Cleaning                       | Prepare datasets by removing duplicates, fixing formats, correcting anomalies 
| 2. Customer Segmentation               | Segment customers by wealth, gender, and job industry                         
| 3. Transaction Analysis                | Analyze sales trends, product performance, and customer purchase behavior     
| 4. New Customer Insights               | Study demographics, location, and revenue potential of new customers          
| 5. CLV Analysis                        | Calculate and analyze Customer Lifetime Value across segments                    
| 6. Executive Summary & Recommendations | Summarize insights and suggest strategies       

🧮 Key Formula – Customer Lifetime Value (CLV)

CLV=(APV×PF)×CL

APV (Average Purchase Value):

APV= NumberofPurchases / TotalRevenue

PF (Purchase Frequency):

PF= UniqueCustomers / TotalTransactions

CL (Customer Lifespan):

Average tenure from Customer Demographic dataset

📊 Deliverables

✔️ Cleaned and analyzed Excel Workbooks (separate for each task)

✔️ Visualizations (charts, graphs, pivot tables)

✔️ Executive summary and recommendations

⚙️ Tools & Technologies

🟢 Microsoft Excel → Data cleaning, pivot tables, charts, analysis


	​

	​


