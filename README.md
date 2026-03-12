# Blinkit Sales Analysis & Business Intelligence Dashboard

## Project Overview
This project performs an end-to-end analysis of the Blinkit grocery sales dataset using **Python for exploratory data analysis (EDA)** and **Power BI for business intelligence visualization**.

The analysis was conducted using Google Collab for Python-based data exploration and Power BI to build an interactive dashboard that highlights key business insights.

The main objective of this project is to analyze Blinkit's retail sales data and identify patterns in **product demand, outlet performance, sales trends, and customer preferences**.

## Tools & Technologies Used

### Data Analysis
- Python
- Pandas
- Matplotlib
- Google Colab

### Visualization
- Power BI

### Version Control
- Git
- GitHub

## Dataset Information

The dataset contains information about grocery items sold by Blinkit, including product attributes, outlet characteristics, sales performance, and customer ratings.

### Dataset Columns

| Column | Description |
|------|-------------|
| Item Fat Content | Indicates whether the product is Low Fat or Regular |
| Item Identifier | Unique identifier for each product |
| Item Type | Category of the item |
| Outlet Establishment Year | Year the outlet was established |
| Outlet Identifier | Unique outlet ID |
| Outlet Location Type | City tier classification |
| Outlet Size | Size of the outlet |
| Outlet Type | Type of retail store |
| Item Visibility | Visibility of the item in the store |
| Item Weight | Weight of the product |
| Sales | Total sales value |
| Rating | Customer rating for the product |

## Key Performance Indicators (KPIs)

The following KPIs were calculated using Python:

| KPI | Value |
|----|------|
| Total Sales | $1.20M |
| Average Sales | $141 |
| Number of Items Sold | 8,523 |
| Average Rating | 3.9 |

These KPIs provide a quick summary of Blinkit's overall sales performance.

## Exploratory Data Analysis

### Sales by Fat Content

- Low Fat Products → **64.6%**
- Regular Products → **35.4%**

Insight:  
Customers show a strong preference for **low-fat grocery products**, suggesting growing demand for healthier options.

### Sales by Product Category

Top performing categories:

| Rank | Category | Sales |
|----|----|----|
| 1 | Fruits & Vegetables | 178K |
| 2 | Snack Foods | 175K |
| 3 | Household Items | 135K |
| 4 | Frozen Foods | 118K |
| 5 | Dairy | 101K |

Insight:  
Blinkit is mainly used for **daily grocery essentials and quick purchases**.


### Sales by Outlet Size

| Outlet Size | Contribution |
|----|----|
| Medium | 42% |
| Small | 37% |
| High | 21% |

Insight:  
Medium sized outlets generate the highest revenue contribution.

### Sales by Outlet Location Tier

| Tier | Sales |
|----|----|
| Tier 3 | Highest |
| Tier 2 | Medium |
| Tier 1 | Lowest |

Insight:  
Tier 3 cities contribute the largest share of sales, indicating strong demand for quick commerce in smaller cities.

### Sales by Outlet Establishment Year

Sales trends show relatively stable performance across different outlet establishment years.

Insight:  
Older outlets may benefit from stronger customer loyalty and established locations.

## Power BI Dashboard

An interactive Power BI dashboard was created to visualize the key metrics and insights derived from the analysis.

The dashboard includes:

- Total Sales
- Average Sales
- Number of Items Sold
- Average Rating
- Sales by Product Category
- Sales by Outlet Size
- Sales by Outlet Location
- Sales by Outlet Establishment Year

This dashboard enables stakeholders to quickly understand Blinkit's sales performance and outlet trends.

## Key Business Insights

1. Low-fat products dominate overall sales.
2. Fruits & Vegetables and Snack Foods generate the highest revenue.
3. Tier 3 cities contribute the most to total sales.
4. Medium-sized outlets perform better compared to small and large outlets.
5. Blinkit demand is primarily driven by daily grocery essentials.

## Repository Structure

```
blinkit-sales-analysis
│
├── Blinkit_Analysis.ipynb        # Python EDA using Google Colab
├── blinkit_dashboard.pbix        # Power BI dashboard
├── blinkit_data.csv              # Dataset used for analysis
├── BlinkIT Grocery Data.xlsx     # Original dataset
└── README.md                     # Project documentation
```

## Conclusion

This project demonstrates how raw retail sales data can be transformed into actionable business insights using Python-based data analysis and Power BI visualization. The analysis highlights key factors influencing Blinkit's sales performance, including product categories, outlet size, and location-based demand patterns.
