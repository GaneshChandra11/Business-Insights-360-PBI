# 📊Business Insights 360📈

### Dashboard Link : 

 📑Project Overview

AtliQ Hardware is growing rapidly in the recent years, and they have decided to implement Data Analytics using Power BI in their company for the first time to surpass their competitors in the market and to make data driven decisions. This project is hoped to give answers to the questions of stakeholders in terms of all aspects like Finance, Sales, Marketing and Supply Chain.

### 👨‍💻Tech Stacks

   - SQL
   - Power BI Desktop
   - Excel
   - DAX language
   - DAX Studio (for optimizing the report)
   - Project charter file

### 🎓Power BI Techniques Learnt

   - What all questions should be asked before staring the Project
   - Creating calculated columns
   - creating measures using DAX language
   - Data modeling
   - Using Bookmarks to switch between visuals
   - Page navigation with buttons
   - Using divide function to prevent zero division errors
   - creating date table using m language
   - Dynamic titles based on the applied filters
   - Using KPI indicators
   - Conditional formatting the values in visuals using icons or background color
   - Data validation techniques
   - Power BI Services
   - Publishing reports to Power BI Services
   - Setting up Personal Gateway to set up the auto refresh of data
   - Power BI App creation
   - Collaboration, workspace, access permissions in Power BI Services
   - And more 😅

### 💼Business Related Terms

   - Gross Price
   - Pre-Invoice Deductions
   - Post-Invoice Deductions
   - Net Invoice Sale
   - Gross Margin
   - Net Sales
   - Net Profit
   - COGS - Cost Of Goods Sold
   - YTD - Year to Date
   - YTG - Year to Go
   - Direct
   - Retailer
   - Distributors
   - Consumer

### 🏬Company’s Background

AltiQ Hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells computer and computer accessories through three mediums/channel

   - Retailers
   - Direct
   - Distributors
     
Recently the company has faced a unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis. The company’s competitors has handful of analytics team to perform analysis and make data driven decision. So, the AltiQ Hardware has no option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry.


Project Kick Off Session, where you should get clear picture of this project and all other questions you have with regards to the project:

### ❓Questions To Ask Before Starting With Dashboard

- What is the objective of building this Power BI Dashboard?<br />
- In what terms the success of this project will be measured?<br />
- What will be time dead-line of the project?<br />
- Do the stakeholders expecting pre-view before the actual release?<br />
- What are all the hopes stakeholders have out of this project?<br />
- what are all the fears stakeholders have in terms of building this dashboard?<br />
- Who all will be using this dashboard and for what purpose?<br />
- what are the expectations of stakeholders, by the completion of this project?<br />
- What can go wrong while building this project?<br />
- what are all the resources/ data needed to build this dashboard?<br />
- is there any inputs from stakeholders in terms of design and views of the dashboard?<br />

After the Project Kick Off Sessions, the data engineering team has given the data as per the request of data analytics team, let’s explore them.

🧐Dataset Understanding

Understanding what data is available will be more helpful while doing analysis. Before jumping on to the analysis get good understanding of what data are available.

Dimension table : It will have the static data like details of customer and products

Fact table : It will have the data about the transactions

### gdb0041
 #### `dim_customer`
 
  - 27 distinct markets (e.g., India, USA, Spain)
  - 75 distinct customers across all markets
  - 2 types of platforms:
    - Brick & Mortar (Physical/Offline store)
    - E-commerce (Amazon, Flipkart)
  - 3 sales channels:
    - Retailer
    - Direct
    - Distributors
 
  #### `dim_market`
  - 27 distinct markets (e.g., India, USA, Spain)
  - 7 sub-zones
  - 4 regions:
    - APAC
    - EU
    - NAN
    - LATAM
 
  #### `dim_product`
  - Divisions:
    - **P & A**: Peripherals, Accessories
    - **PC**: Notebook, Desktop
    - **N & S**: Networking, Storage
  - 14 different categories (e.g., Internal HDD, Keyboard)
  - Different variants available for the same product

### Fact Table
- **Purpose**: Contains transactional data.

#### `fact_forecast_monthly`
- Used for forecasting customer demand in advance, enabling:
  - Higher customer satisfaction
  - Reduced warehouse storage costs
- Denormalized for analytical purposes (Data Warehouse setup)
- All dates in a month are replaced by the start date of the month
- Includes forecast quantity needs per customer

#### `fact_sales_monthly`
- Similar to `fact_forecast_monthly` but records actual sold quantity instead of forecasted values.

### Other Tables

#### gdb056
 #### `freight_cost`
 - Contains travel and other costs for each market by fiscal year.
 
 #### `gross_price`
 - Contains details of gross prices with product codes.
 
 #### `manufacturing_cost`
 - Details of manufacturing costs with product codes and year.
 
 #### `pre_invoice_deductions`
 - Pre-invoice deduction percentages for each customer and year.
 
 #### `post_invoice_deductions`
 - Post-invoice deductions and other deduction details.

### 📥 Importing Data Into Power BI

 - As the database is MySQL in this project, we need to import the datasets from Mysql database to Power BI by providing the Database access credential.

### ✨ Data Model

- Data modeling plays a vital role and is considered the foundation of any report. All visuals are built upon the data model, and poor data modeling can significantly affect the overall performance of the report.
 
- Following good data modeling practices is essential.
- In this project, we have followed the **Snowflake data modeling** method.

![Screenshot 2024-09-09 131550](https://github.com/user-attachments/assets/e92bc3df-4aba-4337-8f6a-5d1c0ee59e40)

### 🎨Dashboard designing
Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

### 🏡Home view

In the Home view, all the buttons for different views will be available. Users can navigate to a specific view page by clicking the corresponding button:

- **Info**
- **Finance View**
- **Sales View**
- **Marketing View**
- **Supply Chain View**
- **Executive View**
- **Support**






https://github.com/user-attachments/assets/10b0807e-db02-40d2-8c2a-e4a99fd3d7be


 





### 💵Finance View

 

https://github.com/user-attachments/assets/d059cc8c-5da2-42cd-b423-1aeb4b4db9ee



 ### 🏷️Sales View
 

https://github.com/user-attachments/assets/6b9cce92-d178-434d-8523-63540fdecfd5



 ### 🛒Marketing View

 

https://github.com/user-attachments/assets/c325c062-432f-4ea6-afa8-f9d77cff0290



 ### 🚚Supply Chain View

 

https://github.com/user-attachments/assets/99d8de81-10ec-4638-b552-1225ebb60ee8



 ### 👨🏻‍💼Executive View

 

https://github.com/user-attachments/assets/bfdfcf76-80d8-493c-92ad-5453a86aca9f




### 🎯Project Outcome
By using this report, decisions can be taken based on the data. Further it will help in answering n number of why questions based on the situations.
