# 🚲 Bicycle Sales Dashboard

An interactive Power BI dashboard for exploring bicycle sales,
profitability, product performance, and regional demand. The report
compares sales and profit across bicycle product categories and analyzes
units sold by state and product to help identify business performance
patterns.

## 📌 Project Overview

This dashboard presents bicycle sales data through interactive
visualizations in Microsoft Power BI. It is designed to make it easier
to compare product performance, identify profitable and unprofitable
product lines, and understand how unit sales vary across states.

## 🛠️ Tech Stack

-   **Power BI Desktop** --- report development and data visualization.
-   **Power Query** --- data preparation and transformation.
-   **DAX (Data Analysis Expressions)** --- calculations and measures,
    where applicable.
-   **Data Modeling** --- organizing fields and relationships to support
    analysis.
-   **File formats** --- `.pbix` for the Power BI report and `.png` for
    dashboard previews.

## 📂 Data Overview

The dashboard uses bicycle sales data with fields represented in the
report such as:

-   **Product** --- bicycle product categories, including City Cycles,
    Kids Cycles, Mountain Cycles, Hybrid Cycles, BMX Cycles, and Road
    Cycles.
-   **State** --- regional sales locations, including Punjab, Delhi,
    Telangana, Bihar, and Tamil Nadu.
-   **Sales** --- sales value by product.
-   **Profit** --- profit or loss by product and average profit by
    state.
-   **Units Sold** --- quantity sold by state, product, and
    product/state combination.



## 🎯 Business Problem

Sales teams need a clear way to compare product performance and regional
demand. Looking at raw transaction data can make it difficult to
identify which bicycle categories contribute most to sales, which
products generate profit or loss, and which states have higher unit
sales.

## 🎯 Dashboard Goals

-   Compare total sales across bicycle products.
-   Identify products with positive profit and products with losses.
-   Compare units sold across states.
-   Understand the product mix within each state's unit sales.
-   Support decisions around product strategy, regional sales planning,
    and profitability review.

## 📊 Features & Visual Highlights

### 1. Sales by Product

A column chart compares total sales across bicycle categories. In the
displayed report, **City Cycles** has the highest sales among the shown
products.

### 2. Profit by Product

A column chart compares profit across products and makes losses visible
below the zero line. The displayed results show positive profit for some
categories and losses for others, highlighting the need to review
product-level profitability.

### 3. Units Sold by State

A column chart compares total units sold across the displayed states:
Punjab, Delhi, Telangana, Bihar, and Tamil Nadu. Punjab has the highest
unit sales among these states in the screenshot.

### 4. Units Sold by State and Product

A stacked column chart breaks each state's unit sales into bicycle
product categories. This helps compare both overall demand and the mix
of products sold in each state.

### 5. Units Sold by State --- Share

A pie chart displays each state's share of units sold, making it easier
to compare regional contributions.

### 6. Average Profit by State

A pie chart compares average profit across states. It provides a quick
view of how average profit differs regionally; the underlying figures
and business context should be reviewed before drawing conclusions about
performance.

### 7. Units Sold by Product --- Share

A pie chart shows the distribution of units sold across bicycle
categories, helping identify which products contribute most to total
volume.

## 💡 Potential Business Insights

-   **Product sales:** City Cycles leads the displayed categories in
    total sales.
-   **Profitability review:** The profit chart shows that sales volume
    alone does not guarantee profitability. Categories with negative
    profit should be investigated for costs, pricing, discounts, and
    margins.
-   **Regional demand:** Punjab has the highest units sold among the
    states displayed in the report.
-   **Product mix:** The state-by-product chart can help teams compare
    regional preferences and plan inventory accordingly.
-   **Further investigation:** Combine sales, profit, and units sold to
    determine whether high-volume products are also profitable.

These observations are based on the supplied screenshots and should be
validated against the complete dataset before being used for business
decisions.

## 📷 Dashboard Screenshots

Add the two dashboard screenshots to your GitHub repository---for
example, inside a folder named `images/`---and use these links:

### Dashboard View 1

![Bicycle Sales Dashboard --- View
1](https://github.com/kerensr053/Bicycle-Sales-Dashboard/blob/main/Bicycle%20Dashboard%201.png)

### Dashboard View 2

![Bicycle Sales Dashboard --- View
2](https://github.com/kerensr053/Bicycle-Sales-Dashboard/blob/main/Bicycle%20Dashboard%202.png)

## 🚀 How to Use

1.  Download or clone this repository.
2.  Open the `.pbix` file using **Power BI Desktop**.
3.  If prompted, configure the data source path and refresh the data.
4.  Explore the report pages and interact with available filters or
    slicers.
5.  Use the visuals to compare product sales, profit, and regional unit
    sales.

## 📁 Suggested Repository Structure

``` text
Bicycle-Sales-Dashboard/
├── README.md
├── Bicycle-Sales-Dashboard.pbix
├── Bicycle Dashboard 1.png
└── Bicycle Dashboard 2.png
```

## 🔮 Possible Future Improvements

-   Add KPI cards for total sales, total profit, total units sold, and
    profit margin.
-   Add slicers for state and product category.
-   Add time-based analysis if transaction dates are available.
-   Include a detailed profit-margin comparison by product and state.
-   Add drill-through pages for product and regional analysis.

## 👤 Author

**Keren Susanna Roy**

- LinkedIn profile: https://www.linkedin.com/in/keren-susanna-roy-649a59228/
- GitHub username: https://github.com/kerensr053


------------------------------------------------------------------------

*Built with Microsoft Power BI to explore bicycle sales, product
profitability, and regional demand.*
