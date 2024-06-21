# Business Insight 360




## Project Overview
AtliQ Hardware is growing rapidly in the recent years, and they have decided to implement the data analytics using PowerBi in their company for the first time to surpass their competitors in the market and to make data driven decisions. This project is hoped to give answers to the questions of stakeholder in terms all the aspects like finance, sales, marketing and supply chain.
I worked on this project by following the Codebasics PowerBi Course, Link to the course is [here](https://codebasics.io/bootcamps/data-analytics-bootcamp-with-practical-job-assistance)

[Live Dashboard link](https://app.powerbi.com/view?r=eyJrIjoiZGE2MzM0ZjktNzk1OC00OTA2LWI3Y2YtZDU5ZjdhY2IzZDdlIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Tech Stack

 - SQL
 - PowerBi Desktop
 - Excel
 - DAX language
 - DAX studio (for optimizing the report)
 - Project charter file



## PowerBi Techniques Learnt

 - What are all the questions should be asked before staring the project
- Creating calculated columns
- creating measure using DAX language
- Data modeling
- Using Bookmarks to switch between two visuals
 - Page navigation with buttons
- Using divide function to prevent zero division errors
- creating date table using m language
- Dynamic titles based on the applied filters
- Using modern KPI indicators
- Usage of Field Farmaters and Bokmarks
- Conditional formatting the values in visuals using icons or background color
- Data validation techniques
- PowerBi services
- Publishing reports to PowerBi services
- Setting up personal gateway to set up the auto refresh of data
- PowerBi App creation
- Collaboration, workspace, access permissions in PowerBi services
## GitHub

- Uploading Large size files using GitHub LFS
- Tracking the particular type of file extensions for LFS
## Business Related Terms

- Gross price
- Pre-invoice deductions
- Post-Invoice deductions
- Net Invoice sale
- Gross Margin
- Net sales
- Net profit
- COGC - cost of goods sold
- YTD - Year to Date
- YTG - Year to Go
- Direct
- Retailer
- Distributors
- Consumer
## Company’s background

AltiQ hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells, computer and computer accessories through three mediums/channel

- Retailers
- Direct
- Distributors
Recently the company has faced a unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis and also the company’s competitors has handful of analytics team to perform analysis and make data driven decision. So, the AltiQ hardware has no other option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry.

Project kick off session, where you should get clear of for what and why this project and all other questions you have with regards to the project

### Questions to ask before starting with dashboard

- What is the objective of building this PowerBi dashboard?
- In what terms the success of this project will be measured?
- What will be time dead-line of the project?
- Do the stakeholders expecting pre-view before the actual release?
- What are all the hopes stakeholders have out of this project?
- what are all fears the stakeholder have in terms of building this dashboard?
- Who are all will be using this dashboard and for what purpose?
- What are all expectation the stakeholders have, by the completion of this project?
- What can go wrong while building this project?
- What are all the resources/ data needed to build this dashboard?
- Is there any inputs from stakeholders in terms of design and views of the dashboard?

After the project kick off meetings, the data engineering team has given the data as per the request of data analytics team, let’s explore them.

### Dataset Understanding

Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get good understanding of what are data available.

Dimension table: It will have the static data like details of customer and products
Fact table : It will have the data about the transactions

- gdb041:
  - dim_customer
    - 27 distinct markets (ex India, USA, Spain)
    - 75 distinct customers thorough out the market
    - 2 types of platforms
      * Brick & Mortars - Physical/offline store
      * E-commerce - Online Store (Amazon, Flipkart)
    - Three channels
      - Retailer
      - Direct
      - Distributors
  - dim_market
    - 27 distinct markets (ex India, USA, Spain)
    - 7 sub-zones
    - 4 regions
      - APAC
      - EU
      - NA
      - LATAM
  - dim_product
    - Divisions
        - P & A
        - Peripherals
        - Accessories
    - PC
        - Notebook
        - Desktop
    - N & S
        - Networking
        - Storage



   - fact_forecast_monthly
        - This table is used to forecast the customer’s need in advance, which can help in
            - Higher customer satisfaction
            - Reduced cost in warehouses for storage purpose
        - The table is denormalized by data engineering team, as it is a data warehouse which is aimed to be used for analytical work.
        - All the date of the month will be replaced by the start date of the month
        - It will have all the column names and in the end it will have the forecast quantity need of the customer
    - fact_sales_monthly
        -This table is more or less is same as fact_forecase_monthly table, but the last column has the value of sold quantity instead of forecast value.

- gdb056
    - freight_cost
        - This table has details of travel cost and other cost for each market with fiscal year
    - gross_price
        - Has the details of gross prices with product code
    - manufacturing_cost
        - Has the details of manufacturing cost with product code with year
    - Pre_invoice_dedutions
        - Has the details of pre invoice deductions percentage for each cutomer with year
    - Post_invoice_deductions
        - Post invoice deductions and other deductions details
## Importing data into PowerBi

- As the database is MySQL in this project, we need to import the datasets from Mysql database to PowerBi by providing the Database access credential
## Data Model

- Data modeling plays a vital role and is considered as the basement of report. All the visuals will be build upon the data model.
- Poor data modeling affects the over all performance of the report.
- Following Good practices of data modeling is must. Refer this page to get to know the good practices Blog
- In this project, we have followed Snowfall data modeling method.

![Data model](https://github.com/nagendravallepu/Business-Insight-360/assets/145926047/fc475fe9-0921-4819-b707-0c76526b8784)

### Dashboard designing

Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required
## Home View

In Home view, all the views button will be available. User will land on specific view page by clicking the button

- Info
- Finance View
- Sales View
- Marketing View
- Supply chain View
- Executive View
- Support

https://github.com/nagendravallepu/Business-Insight-360/assets/145926047/177f2029-3fc7-4534-b82b-782bdfb65386

## Overall Report
https://github.com/nagendravallepu/Business-Insight-360/assets/145926047/db8a6917-7b99-4120-92f0-040573cd21ba

## Finance View
https://github.com/nagendravallepu/Business-Insight-360/assets/145926047/4f99a5bf-45b9-42cb-a253-5dc82e034624

## Sales View
https://github.com/nagendravallepu/Business-Insight-360/assets/145926047/1e10bde3-3dce-4cfb-a436-4287703df5b9

## Marketing View
https://github.com/nagendravallepu/Business-Insight-360/assets/145926047/b2657784-d552-4b8c-b428-96a1fb8ff909

## Supply Chain View
https://github.com/nagendravallepu/Business-Insight-360/assets/145926047/3e5ae2d1-bb9c-44d8-8e79-7495e9b8bd6c

## Executive View
https://github.com/nagendravallepu/Business-Insight-360/assets/145926047/fb37dd3f-c80a-45ff-802d-14b8fb0b1d15

## Project Outcome
By using this report, decisions can be taken based on the data. Further it will help in answering n number of why questions based on the situations.
