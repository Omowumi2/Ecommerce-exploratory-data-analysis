# Ecommerce-exploratory-data-analysis - Project 2
Exploratory Data Analysis (EDA) of 1,200 E-Commerce Orders

## Overview
This project explores a cleaned e-commerce dataset containing 1,200 customer orders. The objective was to transform raw transactional data into actionable business insights using Microsoft Excel.
Through Exploratory Data Analysis (EDA), I examined customer purchasing behavior, sales performance, revenue drivers, order fulfillment trends, and marketing channel effectiveness. The analysis leveraged descriptive statistics, outlier detection, correlation analysis, PivotTables, and PivotCharts to uncover patterns that can support business decision-making.

## Tools Used
Microsoft Excel (Analysis ToolPak, PivotTables, PivotCharts)

## Dataset
The dataset was cleaned in Project 1 before this analysis. It contains 1,200 rows and 14 columns: OrderID | Date | CustomerID | Product | Quantity | UnitPrice | ShippingAddress | PaymentMethod | OrderStatus | TrackingNumber | ItemsInCart | CouponCode | ReferralSource | TotalPrice

## Workbook Structure
| Worksheet        | Description                                    |
| ---------------- | ---------------------------------------------- |
| Clean_data       | Cleaned dataset used for analysis              |
| Descriptive_Stat | Statistical summary of numerical variables     |
| Outlier_check    | IQR-based outlier detection                    |
| Correlation      | Pearson correlation matrix                     |
| Pivot            | PivotTables and PivotCharts                    |
| Working_Data     | Supporting calculations and analysis workspace |

## Analysis and Findings
1. Descriptive Statistics
Descriptive statistics answer the basic question: "What does a typical order look like, and how much do orders vary?" without needing to examine every single row individually.
![Descriptive Stats](images/descriptive_stats.png)

Summary Statistics
| Metric             | TotalPrice | UnitPrice | Quantity | ItemsInCart |
| ------------------ | ---------: | --------: | -------: | ----------: |
| Mean               |  $1,053.97 |   $356.41 |     2.95 |        5.49 |
| Median             |    $823.62 |   $364.21 |     3.00 |        5.00 |
| Standard Deviation |    $819.86 |   $197.18 |     1.41 |        2.28 |
| Minimum            |     $11.39 |    $11.39 |        1 |           1 |
| Maximum            |  $3,456.40 |   $699.93 |        5 |          10 |

Key Insight: The distribution of TotalPrice is moderately right-skewed. The average order value is $1,053.97, while the median order value is $823.62, indicating that a relatively small number of high-value transactions increase the overall average.

Business Interpretation
Median order value provides a more realistic measure of typical customer spending than the mean because it is less affected by unusually large purchases.

