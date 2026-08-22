# 🛒 Grocery Store Sales Analysis Dashboard

> **An end-to-end Microsoft Excel Data Analytics project that transforms raw grocery/e-commerce sales data into an interactive business dashboard for analyzing sales performance, orders, customer demographics, order status, sales channels, and state-wise performance.**

This project demonstrates how **Data Cleaning, Excel Tables, Pivot Tables, Pivot Charts, and Slicers** can be used to convert raw transactional data into a structured and interactive dashboard that supports business-focused analysis and decision-making.

---

## 📊 Project Overview

The **Grocery Store Sales Analysis Dashboard** is an interactive Microsoft Excel dashboard developed to analyze grocery/e-commerce sales data from multiple business perspectives.

The dashboard helps users understand:

- Monthly sales and order trends
- Order status distribution
- Top-performing states by sales
- Orders across different sales channels
- Customer orders by age group and gender
- Sales contribution by gender
- Performance based on Month, Channel, and Category

The main goal is to move from:

**Raw Data → Clean Data → Analysis → Visualization → Business Insights**

This project focuses on using Excel as a practical Data Analytics and Business Intelligence tool rather than simply creating charts.

---

## 🔍 Business Problem

Grocery and e-commerce businesses generate large volumes of sales and order data. Raw transactional data can be difficult to understand without proper analysis and visualization.

Business users need to quickly answer questions such as:

- Which months generate higher sales and order volumes?
- What is the distribution of delivered, cancelled, refunded, and returned orders?
- Which states contribute strongly to sales?
- Which sales channels generate more orders?
- Which customer age groups place more orders?
- How do male and female customers compare?
- How does performance change by month, channel, or category?

### The Challenge

The raw sales data needs to be transformed into an easy-to-understand reporting system where users can **filter, compare, and analyze business performance without manually reviewing individual transactions**.

### The Approach

The project uses Microsoft Excel to:

**Raw Data → Data Cleaning → Structured Tables → Pivot Analysis → Interactive Charts → Slicers → Business Insights**

### Business Value

The dashboard provides a single interactive view of important sales and customer metrics, helping users **identify performance patterns, compare business segments, and explore business data more efficiently**.

---

## 🎯 Project Objectives

The key objectives of this project were to:

- Clean and prepare the raw sales data for analysis
- Structure the dataset using Excel Tables
- Analyze monthly sales and order performance
- Compare sales amount with order count
- Analyze order status distribution
- Identify the Top 10 states by sales
- Compare orders across different sales channels
- Analyze orders by age group and gender
- Compare sales performance by gender
- Build an interactive Excel dashboard
- Use slicers for dynamic data exploration
- Present business-oriented insights through visual analysis
- Make the analysis easy for non-technical users to explore

---

## 📁 Dataset Description

The project is based on **grocery/e-commerce store sales transaction data**.

The dataset contains information required for analysis across areas such as:

- Sales Amount
- Order Information
- Order Status
- State
- Sales Channel
- Customer Age Group
- Gender
- Product Category
- Month

### Data Flow

Raw Grocery Sales Data
        ↓
Data Cleaning & Preparation
        ↓
Cleaned / Structured Data
        ↓
Pivot Tables
        ↓
Pivot Charts
        ↓
Interactive Slicers
        ↓
Excel Sales Dashboard
        ↓
Business Insights

### Raw Data

The raw dataset represents the original source data before cleaning and preparation.

**File:**

`data/raw/grocery_store_raw_data.xlsx`

### Cleaned Data

The cleaned dataset represents the prepared version used for analysis and dashboard development.

**File:**

`data/cleaned/grocery_store_cleaned_data.xlsx`

> **Note:** Include the cleaned-data file only if it actually exists in the repository. Do not claim that a cleaned dataset exists if it has not been provided.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Microsoft Excel** | Data cleaning, analysis and dashboard development |
| **Excel Tables** | Structured data management |
| **Pivot Tables** | Data aggregation and analysis |
| **Pivot Charts** | Business data visualization |
| **Slicers** | Interactive filtering |
| **Data Cleaning** | Preparing raw data for reliable analysis |
| **Dashboard Design** | Presenting insights clearly |

### Core Skills

`Microsoft Excel` `Data Cleaning` `Data Analysis` `Pivot Tables` `Pivot Charts` `Slicers` `Data Visualization` `Dashboard Design` `Business Intelligence`

---

## 🧹 Data Preparation & Cleaning

Before creating the dashboard, the raw data was reviewed and prepared for analysis.

The data preparation process included:

- Reviewing the raw dataset structure
- Checking data consistency
- Organizing data into an Excel Table
- Reviewing fields required for analysis
- Preparing categorical fields
- Preparing month/date information for monthly analysis
- Ensuring values were suitable for Pivot Table analysis
- Structuring the data for dashboard reporting

### Data Preparation Workflow

Raw Dataset
     ↓
Data Quality Review
     ↓
Cleaning & Formatting
     ↓
Structured Excel Table
     ↓
Pivot Tables
     ↓
Pivot Charts
     ↓
Interactive Dashboard

The purpose of this step was to create a **consistent and analysis-ready dataset** before building the dashboard.

---

# 📊 Dashboard Features

The dashboard contains multiple business-focused analyses.

---

## 1. 📈 Monthly Sales & Orders Analysis

The dashboard compares **Order Count** and **Sales Amount** from **January to December**.

This analysis helps users:

- Monitor monthly sales performance
- Compare order volume across months
- Compare order count with sales amount
- Identify changes in sales activity over time

Comparing sales and orders provides a better understanding of business performance than looking at either metric individually.

---

## 2. 📦 Order Status Analysis

The dashboard analyzes orders based on their status:

- Delivered
- Cancelled
- Refunded
- Returned

This analysis helps users understand the distribution of different order outcomes and provides a starting point for investigating operational performance.

---

## 3. 🗺️ Top 10 States by Sales

The dashboard identifies the **Top 10 states based on sales performance**.

This analysis helps users:

- Compare state-wise sales
- Identify leading geographic markets
- Understand geographic sales distribution
- Focus further analysis on high-performing regions

---

## 4. 🛍️ Orders by Sales Channel

Orders are analyzed across the following sales channels:

- Ajio
- Amazon
- Flipkart
- Meesho
- Myntra
- Nalli
- Others

This analysis allows users to compare order activity across different e-commerce channels.

---

## 5. 👥 Orders by Age Group & Gender

The dashboard analyzes order activity across different age groups and genders.

### Age Groups

- Adult
- Senior
- Teenager

### Gender

- Male
- Female

This analysis provides a demographic view of customer order behavior and allows users to compare different customer segments.

---

## 6. ⚥ Sales by Gender

Sales are compared between:

- Men
- Women

This analysis helps users understand the distribution of sales across gender segments.

---

# 🎛️ Interactive Slicers

The dashboard contains three interactive slicers:

### 📅 Month

The **Month slicer** allows users to filter the dashboard for a specific month and explore the corresponding sales and order performance.

### 🛍️ Channel

The **Channel slicer** allows users to filter the dashboard by sales channel such as:

- Ajio
- Amazon
- Flipkart
- Meesho
- Myntra
- Nalli
- Others

This makes it easier to analyze individual sales channels.

### 🏷️ Category

The **Category slicer** allows users to filter the dashboard based on product category.

This helps users understand how different categories contribute to business performance.

### Why Slicers Matter

Instead of manually changing Pivot Tables or creating separate reports, users can interactively filter the dashboard and explore different business segments.

### Interactive Analysis Flow

Select Month
     +
Select Channel
     +
Select Category
     ↓
Dashboard Filters Update
     ↓
Analyze Selected Business Segment

The slicers make the dashboard more interactive and allow users to perform focused analysis without manually changing the underlying Pivot Tables.

---

# 📈 Analysis Performed

The project performs the following business analyses:

| Analysis | Business Purpose |
|---|---|
| **Monthly Sales** | Understand sales performance across months |
| **Monthly Orders** | Monitor order volume over time |
| **Sales vs Orders** | Compare sales value with order activity |
| **Order Status** | Understand delivered, cancelled, refunded and returned orders |
| **Top 10 States** | Identify leading geographic markets |
| **Channel Analysis** | Compare order activity across sales channels |
| **Age Group Analysis** | Understand customer order distribution by age |
| **Gender Analysis** | Compare customer orders and sales by gender |
| **Slicer Analysis** | Explore performance dynamically by Month, Channel and Category |

The focus of the project is not simply to create charts, but to use the available data to answer **business-oriented questions**.

---

# 💡 Key Business Insights

The dashboard is designed to help users identify insights across several business areas.

### 📈 Sales Performance

- Compare sales activity across January to December.
- Identify months with relatively higher or lower sales activity.
- Compare sales amount with order count.
- Understand whether changes in order volume are reflected in sales performance.

### 📦 Order Fulfillment

- Understand the distribution of delivered, cancelled, refunded, and returned orders.
- Identify order-status patterns that may require further operational investigation.

### 🗺️ Geographic Performance

- Identify the Top 10 states by sales.
- Compare sales contribution across different states.
- Identify leading geographic markets for further analysis.

### 🛍️ Sales Channel Performance

- Compare order activity across Ajio, Amazon, Flipkart, Meesho, Myntra, Nalli, and Others.
- Identify channels with stronger order activity.
- Use the Channel slicer to perform focused channel-level analysis.

### 👥 Customer Analysis

- Compare orders across Adult, Senior, and Teenager age groups.
- Compare Male and Female order activity.
- Analyze sales distribution between Men and Women.

### 🎛️ Interactive Analysis

- Filter the dashboard by Month.
- Filter the dashboard by Channel.
- Filter the dashboard by Category.
- Compare different business segments dynamically.

> **Important:** No fixed numerical business results are claimed in this README because the actual results depend on the dataset included in the project.

---

# 🖼️ Dashboard Preview

## 📊 Dashboard Overview

<!--
ADD IMAGE HERE

Upload the image to:

screenshots/dashboard-overview.png

Then GitHub will automatically display it using the Markdown image below.
-->

![Dashboard Overview](screenshots/dashboard-overview.png)

The dashboard overview provides a consolidated view of sales, orders, order status, state performance, sales channels, customer demographics, and interactive filters.

---

## 📈 Sales vs Orders Analysis

<!--
ADD IMAGE HERE

Upload the image to:

screenshots/sales-vs-orders.png

Then GitHub will automatically display it using the Markdown image below.
-->

![Sales vs Orders Analysis](screenshots/sales-vs-orders.png)

This view compares monthly sales amount and order count to understand sales activity across the year.

---

## 📦 Order Status Analysis

<!--
ADD IMAGE HERE

Upload the image to:

screenshots/order-status.png

Then GitHub will automatically display it using the Markdown image below.
-->

![Order Status Analysis](screenshots/order-status.png)

This visualization shows the distribution of delivered, cancelled, refunded, and returned orders.

---

## 🗺️ Top 10 States by Sales

<!--
ADD IMAGE HERE

Upload the image to:

screenshots/top-10-states.png

Then GitHub will automatically display it using the Markdown image below.
-->

![Top 10 States by Sales](screenshots/top-10-states.png)

This visualization highlights the Top 10 states based on sales performance.

---

## 🛍️ Sales Channel Analysis

<!--
ADD IMAGE HERE

Upload the image to:

screenshots/channel-analysis.png

Then GitHub will automatically display it using the Markdown image below.
-->

![Sales Channel Analysis](screenshots/channel-analysis.png)

This visualization compares order activity across the available sales channels.

---

# 📁 Project Structure

```text
Grocery-Store-Sales-Analysis-Excel/
│
├── README.md
│
├── data/
│   ├── raw/
│   │   └── grocery_store_raw_data.xlsx
│   │
│   └── cleaned/
│       └── grocery_store_cleaned_data.xlsx
│
├── dashboard/
│   └── Grocery_Store_Sales_Dashboard.xlsx
│
├── screenshots/
│   ├── dashboard-overview.png
│   ├── sales-vs-orders.png
│   ├── order-status.png
│   ├── top-10-states.png
│   └── channel-analysis.png
│
└── documentation/
    └── project-notes.md
