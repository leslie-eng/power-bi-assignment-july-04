# Power BI Sales Dashboard

A complete Power BI project demonstrating the end-to-end analytics workflow—from preparing a raw dataset to building an interactive business dashboard for **LuxCars Logistics**.

---

# Project Overview

This project analyzes vehicle sales and logistics data using Power BI. The objective is to transform a raw CSV dataset into an interactive dashboard that enables business users to monitor sales performance, profitability, logistics, customer behavior, and branch performance.

The project follows a standard business intelligence workflow:

1. Import the raw dataset.
2. Clean and transform the data.
3. Design a star schema.
4. Create DAX measures.
5. Build interactive dashboard visuals.
6. Generate business insights and recommendations.

---

# Dataset

**Dataset:** `Jcars_logistics_dataset_v2.csv`

The dataset contains information about:

* Vehicle sales
* Customers
* Sales representatives
* Branches and regions
* Delivery information
* Vehicle details
* Revenue
* Logistics costs
* Customer ratings
* Payment methods

---

# Step 1 – Data Cleaning (Power Query)

The raw dataset was cleaned before analysis.

Typical transformations included:

* Removing duplicate records
* Handling missing values
* Correcting data types
* Standardizing column names
* Formatting dates
* Creating calculated columns where necessary
* Removing unnecessary columns
* Validating numerical values

After cleaning, the dataset was ready for modelling.

---

# Step 2 – Data Modelling

The dataset was transformed into a **star schema**.

Dimension tables include:

* Customer Dimension
* Car Dimension
* Sales Representative Dimension
* Location Dimension

The fact table stores transactional sales data including:

* Revenue
* Units sold
* Delivery fee
* Logistics cost
* Customer ratings
* Days to deliver
* Payment information

Relationships were created between the fact table and each dimension using their respective primary keys.

This model improves:

* Query performance
* Report readability
* DAX efficiency
* Scalability

---

# Step 3 – DAX Measures

Several measures were created to support business reporting.

Examples include:

* Total Revenue
* Gross Profit
* Gross Profit Margin
* Total Cars Sold
* Number of Orders
* Average Delivery Days
* Average Branch Rating
* Top Car Make
* Highest Revenue Branch
* Highest Revenue Sales Representative
* Highest Revenue Vehicle Type
* Highest Revenue Region
* Highest Revenue Payment Method
* Highest Customer Lead Source

These measures allow the dashboard to dynamically respond to filters and user interactions.

---

# Step 4 – Dashboard Design

The dashboard provides an executive overview of business performance.

## Dashboard Components

### KPI Cards

Key performance indicators include:

* Total Revenue
* Gross Profit
* Total Cars Sold
* Average Delivery Days
* Average Branch Rating

### Interactive Filters

Users can filter the dashboard by:

* Branch
* Date

All visuals update automatically based on the selected filters.

### Charts

The dashboard includes visualizations for:

* Sales performance
* Best-selling vehicle brands
* Customer types generating the highest revenue
* Monthly Revenue Trend
* Monthly Units Sold
* Monthly Gross Profit

### Tables

A table displays:

* Sales Representative
* Lead Source
* Cumulative Revenue

### Matrix

A matrix summarizes:

* Branch Name
* Branch Rating
* Total Revenue
* Units Sold

### Drill-through Page

A dedicated branch details page provides:

* Total Revenue
* Gross Profit
* Top Vehicle by Revenue
* Highest Performing Sales Representative
* Lead Source
* Payment Status
* Monthly Revenue Trend
* Delivery Status

---

# Business Insights

Analysis of the dashboard revealed the following:

* Nakuru branch recorded the highest logistics cost relative to revenue.
* SUVs were the best-selling vehicle category.
* Toyota was the top-selling vehicle brand.
* Revenue showed a downward trend throughout the year.
* Government institutions and car dealers generated the highest customer revenue.
* Kakamega branch generated the highest overall revenue.
* M-Pesa contributed the highest payment revenue.
* Delivered orders represented the largest delivery status category.
* Nissan pickups experienced the highest number of returns.
* Faith Achieng generated the highest sales revenue among sales representatives.

---

# Business Recommendations

Based on the analysis:

* Review pricing strategies to improve profit margins.
* Reduce logistics and delivery expenses by optimizing transportation operations.
* Increase investment in high-performing marketing channels such as Instagram and Facebook.
* Investigate the causes of declining monthly revenue.
* Review the return process for Nissan pickups to identify quality or operational issues.
* Replicate successful practices from the Kakamega branch across other branches.
* Continue promoting digital payment methods due to their strong revenue contribution.

---

# Skills Demonstrated

* Power Query
* Data Cleaning
* Data Transformation
* Data Modelling
* Star Schema Design
* Relationship Management
* DAX
* Data Visualization
* Business Intelligence
* Dashboard Design
* Business Analytics

---

# Tools Used

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)
* CSV Dataset

---

# Conclusion

This project demonstrates a complete Power BI analytics workflow, beginning with a raw dataset and progressing through data cleaning, modelling, relationship creation, DAX development, and dashboard design. The resulting dashboard provides actionable business insights that support decision-making in sales, logistics, and operational performance.
