# Electroincs Ecommerce Funnel Analysis
Table of Contents:
- [Project Background](https://github.com/jiayuanshi/Electronics-Ecommerce-Funnel-Analysis?tab=readme-ov-file#project-background)
- [Executive Summary](https://github.com/jiayuanshi/Electronics-Ecommerce-Funnel-Analysis?tab=readme-ov-file#executive-summary)
- [Insights Deep-Dive](https://github.com/jiayuanshi/Electronics-Ecommerce-Funnel-Analysis?tab=readme-ov-file#insights-deep-dive)
    - [Monthly Sales Trends & Growth Rates](https://github.com/jiayuanshi/Electronics-Ecommerce-Funnel-Analysis?tab=readme-ov-file#monthly-sales-trends--growth-rates)
    - [Key Categories Performance](https://github.com/jiayuanshi/Electronics-Ecommerce-Funnel-Analysis?tab=readme-ov-file#key-categories-performance)

## Project Background
In this project, we are going to dive through the datasets of an ecommerce online shop's user event history in electronics field specifically with the purpose of improving budget relocation for sales, product, and marketing. With over 800k instances collected by Open CDP project, we will perform sale trend, funnel, and product analysis with time dimension of 5 months (Oct 2020-Feb 2021). 

## Executive Summary
The store's 5-month records show monthly revenue fluctuating around $0.9 million, with a continuously increasing trend from October 2020 to January 2021 but a slightly decrease in February 2021. Among all categories of product, `computers` has contributed to the greatest proportion of sales, 87%, whereas `electronics` products account for 11% of revenue, ranking in the 2nd. The conversion rate of view to cart has increased from 7% to 9% though the purchase conversion rate has dropped from 72% to 65% could be a potential concern. The store can benefit from expanding top product lines and shifting focuses to frequently viewed products. Targeted improvements to low purchase conversion rate products will drive sustainable growth for the store.

## Insights Deep-Dive
### Monthly Sales Trends & Growth Rates
![Fig 1](Visualization/MonthlySales.png "Sales by Category")
- The store has acheived $0.8 million in monthly sales with 4919 orders per month.
- The two obvious growths of total revenue has reflected the seasonality of sales, especially in November and Janurary, which corresponds to revenue growth of 43% and 99% (almost doubled!!) respectively.
- During the 5 months, revenue and orders growth fluactuated with different direction but a good sign is that the average order value (AOV) has increased steadily, showing an uptrend in customers' consumption power.

### Key Categories Performance
![Fig 2](Visualization/CategorySales.png "Monthly Sales by Category")
![Fig 3](Visualization/MonthlyMetrics.png "Monthly Sales by Category")

- Among the four categories, `computers` and `electronics` has contributed to 98% of total revenue.
- `Computers` accounts for 87% of total revenues and 69% of total orders (16870 orders). Simultaneously, it is also the category with highest AOV, $221 per order. 
- There are two peaks in `computers`'s total orders graph -- Nov 2020 and Jan 2021, which can be related to Black Friday and education preparation.
- Although `accessories` only engaged with little revenue and order amount (approximately 0% for both), there's a dramatic increase by growth rates in Dec 2020, showing its popularity in gift selection for fesival.

## Clarifying Questions, Assumptions, and Caveats
### Questions for Stakeholders
### Assumptions & Caveats
- **Product Categories Selection**
    - Due to our goal of exploring electronics related products only and with consideration of data integrety, the categories successfully passed the quality check are `accessories`, `appliances`,  `computers`, and `electronics`. 
