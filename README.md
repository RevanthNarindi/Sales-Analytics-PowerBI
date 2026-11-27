# 📊 Sales Analytics Dashboard | Power BI

An interactive Sales Analytics Dashboard built using **Microsoft Power BI** to analyze sales performance, profitability, product contribution, customer performance, regional trends, and sales targets.

This project demonstrates an end-to-end data analytics workflow, covering data preparation, data transformation, data modelling, DAX calculations, and interactive dashboard development.

---

## 🎯 Project Overview

The objective of this project is to transform raw sales data into meaningful business insights through interactive visualizations and analytical measures.

The dashboard helps explore sales performance across different dimensions, identify business trends, evaluate profitability, understand customer and product contributions, and compare actual sales against business targets.

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** – Dashboard development and data visualization
- **Power Query** – Data cleaning and transformation
- **DAX (Data Analysis Expressions)** – Measures and analytical calculations
- **Microsoft Excel / CSV** – Data sources
- **Data Modelling** – Relationships between fact and dimension tables

## 📸 Dashboard Preview

Explore the interactive dashboard and its different analytical views.

![Sales Analytics Dashboard](Screenshots/Sales_Overview.png)

*The dashboard provides an overview of sales performance, profitability, and regional and category-wise analysis.*

## 📌 Key Features & Analysis

### 1. Sales & Profit Analysis
- Total Sales and Profit Percentage
- Sales performance by Category
- Profit analysis by Region
- Total Cost and Net Sales analysis

### 2. Time Intelligence Analysis
- Average Sales by Day
- Moving Average Sales
- Current Year vs Last Year Sales
- Month-wise Sales Analysis
- Cumulative Sales Analysis

### 3. Product & Customer Analysis
- Top N Product Analysis
- Top 3 Product Sales Contribution
- Top 3 Product Share Percentage
- Top 3 Customer Sales
- Top 3 Customer Share Percentage

### 4. Sales Target Analysis
- Actual Sales vs Target Sales
- Dynamic Target Percentage Parameter
- Difference from Target
- Target Achievement Analysis
- KPI and Gauge Visualizations

### 5. Customer Segment Analysis
- Consumer Segment
- Corporate Segment
- Home Office Segment
- Sales and Profitability Analysis by Segment

## 📈 Dashboard Pages

The report contains the following analytical pages:

| Dashboard Page | Analysis |
|---|---|
| Home | Project introduction and key performance areas |
| Total Sales and Profit % | Sales and profitability by category and region |
| Average Sales | Daily average sales and moving average trends |
| All Sales Parameter | Regional, category and monthly sales analysis |
| Top N Sales and Shares | Top products and sales contribution |
| Current Sales vs Target | Actual sales, targets and variance analysis |
| Consumer Segment | Consumer sales performance |
| Corporate Segment | Corporate sales performance |
| Home Office Segment | Home Office sales performance |

## ⚙️ Data Preparation & Transformation

Data preparation and transformation were performed using Power Query.

Key activities included:

- Importing sales data and supporting dimension tables.
- Combining sales datasets from different periods.
- Promoting headers and correcting data types.
- Removing unnecessary columns and duplicate records.
- Handling null values and filtering invalid Order IDs.
- Merging sales records with sales return information.
- Preparing customer, product, region, and calendar tables.

## 🧮 DAX Measures & Calculations

DAX was used to create analytical measures and support interactive reporting.

Some important calculations include:

| Measure | Purpose |
|---|---|
| Total Sales | Calculates total sales |
| Total Cost | Calculates total cost |
| Net Sales | Calculates sales excluding returned records |
| Net Profit | Calculates net sales minus net cost |
| Profit % | Evaluates profitability |
| Average Sales | Calculates average sales |
| Moving Average Sales | Analyzes sales trends over time |
| Last Year Sales | Compares previous-year performance |
| MTD Sales | Calculates month-to-date sales |
| YTD Sales | Calculates year-to-date sales |
| Top 3 Product Share | Measures top-three product contribution |
| Top 3 Customer Share | Measures top-three customer contribution |
| Target Sales | Calculates sales targets using a dynamic percentage |
| Difference from Target | Measures actual sales against target |

## 🗂️ Repository Structure

```text
Sales-Analytics-PowerBI/
│
├── Dashboard/
│   └── Sales_Analytics.pbix
│
├── Dataset/
│   └── Sales_Data.xlsx
│
├── Documentation/
│   ├── Data_Documentation.pdf
│   └── Visual_Documentation.pdf
│
├── Screenshots/
│   ├── Home.png
│   ├── Sales_Overview.png
│   └── Product_Analysis.png
│
└── README.md
```

## 🚀 How to Use This Project

1. Clone or download this repository.
2. Open the `Dashboard` folder.
3. Download and open the `.pbix` file using Microsoft Power BI Desktop.
4. If prompted, configure the source file path to the dataset.
5. Refresh the data if required.
6. Explore the dashboard using the available filters, slicers, bookmarks, and navigation buttons.

## 📚 Project Documentation

Detailed documentation is available in the repository:

- **[Data Documentation](Documentation/Data_Documentation.pdf)** – Covers data preparation, Power Query transformations, data modelling, relationships, and DAX measures.
- **[Visual Documentation](Documentation/Visual_Documentation.pdf)** – Covers report layout, visual formatting, slicers, parameters, bookmarks, and navigation.

## 💡 Key Learnings

Through this project, I gained practical experience in:

- Cleaning and transforming data using Power Query.
- Creating and managing relationships between tables.
- Writing DAX measures for business analysis.
- Applying time intelligence calculations.
- Developing interactive Power BI dashboards.
- Implementing dynamic parameters and bookmarks.
- Translating business requirements into meaningful visual insights.

## 👨‍💻 Author

**Revanth Narindi**

Aspiring Data Analyst | Power BI | SQL | Excel | Data Analytics

🔗 **LinkedIn:** [Connect with me on LinkedIn](https://www.linkedin.com/in/revanth-narindi/)

---

⭐ If you find this project useful, feel free to explore the repository and connect with me!
