# kayaas_store_excel_project
This is an entry level excel project of a local store,based on annual sales report 
# Kayaas Store Dashboard --- Annual Report 2022

## 📊 Project Overview

The **Kayaas Store Dashboard -- Annual Report 2022** is an interactive
sales and order analysis dashboard designed to provide a consolidated
view of business performance for the year 2022.

The dashboard helps users analyze **sales, orders, customers, product
categories, sales channels, order status, customer age groups, states,
and product sizes**. Interactive slicers allow the analysis to be
filtered by **Month, Channel, and Category**.

------------------------------------------------------------------------

## 🎯 Dashboard Objectives

The main objectives of this dashboard are:

-   Monitor overall sales performance.
-   Track the number of SKUs/orders.
-   Compare sales and order trends month by month.
-   Understand the distribution of customers by gender.
-   Analyze orders by sales channel.
-   Identify the most important product categories.
-   Monitor order status such as Delivered, Cancelled, Refunded, and
    Returned.
-   Compare customer activity across age groups and gender.
-   Identify the top-performing states by sales.
-   Analyze SKU distribution across categories.
-   Understand quantity sold by product size.

------------------------------------------------------------------------

## 📌 Key Performance Indicators

The dashboard displays the following headline KPIs:

  KPI              Value shown in dashboard
  -------------- --------------------------
  Total Sales                  ₹2,14,41,209
  Count of SKU                       31,047
  Men                                 9,494
  Women                              21,553

> **Note:** The KPI values shown above are the values can change when slicers/filters
> are applied.

------------------------------------------------------------------------

## 🎛️ Interactive Filters

The dashboard provides three major filter areas:

### Month

Users can select individual months such as:

-   Jan
-   Feb
-   Mar
-   Apr
-   May
-   Jun
-   Jul
-   Aug
-   Sep
-   Oct
-   Nov
-   Dec

### Channel

The available sales channels shown are:

-   Ajio
-   Amazon
-   Flipkart
-   Meesho
-   Myntra
-   Nalli
-   Others

### Category

The available product categories shown are:

-   Blouse
-   Bottom
-   Ethnic Dress
-   Kurta
-   Saree
-   Set
-   Top
-   Western Dress

These slicers make the dashboard interactive and allow users to perform
focused analysis.

------------------------------------------------------------------------

# 📈 Dashboard Visuals

## 1. Orders vs Sales

This combination chart compares:

-   **Sum of Amount (Sales)** using columns.
-   **Count of Order ID (Orders)** using a line.

The monthly view helps identify changes in sales and order volume
throughout 2022.

March has the highest visible order count at
approximately **2,819**, while monthly sales remain around the
₹1.6M--₹1.9M range.

------------------------------------------------------------------------

## 2. Percentagewise Sales

The pie chart shows the percentage distribution of sales/orders between:

-   Men
-   Women

The dashboard indicates approximately:

-   **Women: 64%**
-   **Men: 36%**

This highlights the larger contribution from women customers in the
displayed data.

------------------------------------------------------------------------

## 3. Order Status

This chart displays the number of orders by status:

-   Cancelled --- 844
-   Delivered --- 28,641
-   Refunded --- 517
-   Returned --- 1,045

The majority of orders are **Delivered**, indicating a strong proportion
of successfully completed orders.

------------------------------------------------------------------------

## 4. Orders: Sales by Age Group

This clustered column chart compares **Men vs Women** across customer
age groups:

-   Adults
-   Senior
-   Teenagers
-   Young

The displayed percentages show that the **Young** customer group has the
largest contribution, particularly among women.

Approximate visible percentages include:

  Age Group        Men    Women
  ----------- -------- --------
  Adults         8.51%   19.43%
  Senior         3.92%    8.84%
  Teenagers      0.69%    1.70%
  Young         17.46%   39.45%

------------------------------------------------------------------------

## 5. Orders by Channels

The donut chart shows order distribution across sales channels.

Visible values include:

  Channel               Orders   Approx. Share
  ---------- ----------------- ---------------
  Amazon                11,016             35%
  Myntra                 7,254             23%
  Flipkart               6,703             22%
  Ajio                   1,931              6%
  Meesho                 1,398              5%
  Nalli                  1,484              5%
  Others       Remaining share             ---

**Amazon** is the largest visible sales channel by order count.

------------------------------------------------------------------------

## 6. Sales --- Top 5 States

The horizontal bar chart identifies the top five states by sales.

Visible values are approximately:

  State              Sales
  --------------- --------
  Maharashtra       ₹2.99M
  Karnataka         ₹2.65M
  Uttar Pradesh     ₹2.10M
  Telangana         ₹1.71M
  Tamil Nadu        ₹1.68M

**Maharashtra** is the top-performing state among the five shown.

------------------------------------------------------------------------

## 7. Orders Percentage

This pie chart shows the percentage distribution of orders according to
order status.

The dashboard shows approximately:

-   **Delivered: 92%**
-   Cancelled: \~3%
-   Returned: \~3%
-   Refunded: \~2%

This provides a quick view of successful versus unsuccessful order
outcomes.

------------------------------------------------------------------------

## 8. Category-wise SKUs

This horizontal bar chart compares SKU counts across product categories.

Visible values include:

  Category          SKU Count
  --------------- -----------
  Set                  12,391
  Kurta                10,446
  Western Dress         4,066
  Top                   2,193
  Saree                 1,380
  Ethnic Dress            264
  Blouse                  229
  Bottom                   78

**Set** and **Kurta** have the highest SKU counts in the displayed
dashboard.

------------------------------------------------------------------------

## 9. Total Quantity by Sizes

This chart displays the total quantity sold for different product sizes.

The visible sizes include:

-   M
-   L
-   XL
-   S
-   XXL
-   3XL
-   XS
-   Free
-   6XL
-   5XL
-   4XL

The highest visible quantity is for **M**, followed by **L** and **XL**.

------------------------------------------------------------------------

# 🔎 Key Business Insights

Based on the dashboard screenshot:

1.  **Women contribute a larger share** of the displayed customer/order
    distribution than men.
2.  **Amazon is the leading sales channel** by visible order count,
    followed by Myntra and Flipkart.
3.  **Delivered orders dominate the order-status distribution**,
    accounting for approximately 92% of orders.
4.  **Young customers represent the largest age-group contribution**,
    particularly women.
5.  **Maharashtra is the leading state** among the displayed top five
    states by sales.
6.  **Set and Kurta** are the two categories with the highest visible
    SKU counts.
7.  **Medium (M) size** has the highest visible quantity sold.
8.  Monthly analysis shows noticeable variation in both sales and order
    volume, with **March showing the highest visible order count**.

------------------------------------------------------------------------

# 🛠️ Tools / Technologies

The dashboard is designed as a business intelligence report and can be
implemented using:

-   **Microsoft Power BI / Excel**
-   use Excel for data cleaning and transformation
-   Interactive slicers and dashboard visuals

------------------------------------------------------------------------

# 📐 Dashboard Design

The dashboard follows a structured layout:

### Top Section

-   Total Sales KPI
-   Count of SKU KPI
-   Men/Women KPI
-   Month slicer
-   Channel slicer
-   Category slicer

### Middle Section

-   Orders vs Sales
-   Percentagewise Sales
-   Order Status
-   Orders by Age Group

### Bottom Section

-   Orders by Channels
-   Top 5 States by Sales
-   Orders Percentage
-   Category-wise SKUs
-   Total Quantity by Sizes

This layout allows users to move from **high-level KPIs → trends →
customer/channel analysis → geographic and product analysis**.

------------------------------------------------------------------------

# 🚀 How to Use the Dashboard

1.  Open the dashboard/report.
2.  Review the KPI cards for the overall business picture.
3.  Select a **Month** to analyze a particular period.
4.  Select one or more **Channels** to compare marketplace performance.
5.  Select a **Category** to focus on a particular product group.
6.  Observe how the charts and KPIs change based on the selected
    filters.
7.  Use the dashboard to identify trends, high-performing segments, and
    potential areas for improvement.

------------------------------------------------------------------------

# 📁 Recommended Project Structure

``` text
Kayaas-Store-Dashboard/
│
├── README.md
├── Dataset/
│   └── Kayaas_Store_2022.xlsx
│
├── Dashboard/
│   └── Kayaas_Store_Dashboard.pbix
│
└── Screenshots/
    └── dashboard.png
```

------------------------------------------------------------------------

# 💡 Possible Future Enhancements

The dashboard can be extended with:

-   Year-over-year sales comparison.
-   Profit and profit-margin analysis.
-   Average order value.
-   Return and cancellation rate KPIs.
-   Channel-wise revenue and profitability.
-   State-level geographic visualization.
-   Customer retention analysis.
-   Monthly growth percentage.
-   Top and bottom products by revenue.
-   Drill-through pages for product, channel, and state analysis.

------------------------------------------------------------------------

## 📌 Conclusion

The **Kayaas Store Dashboard Annual Report 2022** provides a single
interactive view of sales and order performance. It combines KPI cards,
trend analysis, customer segmentation, channel analysis, geographic
performance, product-category analysis, order-status analysis, and
size-level quantity analysis.

The dashboard can help business users quickly answer questions such as:

-   How much sales were generated?
-   Which channel receives the most orders?
-   Which customer segment contributes the most?
-   Which states generate the highest sales?
-   Which product categories have the most SKUs?
-   What percentage of orders are successfully delivered?
-   Which product sizes have the highest demand?

Overall, the dashboard converts raw store/order data into an
**interactive business-performance report for 2022**.
