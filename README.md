# Awesome Chocolates Sales Dashboard

An interactive Power BI dashboard built to analyze sales, shipments, costs, and profitability for a chocolate manufacturing and distribution business across multiple countries.

![Dashboard Overview](cocolate_sales_overview.png)

## Problem Statement

Awesome Chocolates operates across multiple countries and sells through a large sales team, but leadership has no single view of how sales, costs, and shipments are performing across regions or individual salespeople. Without this visibility, it is hard to spot which markets are underperforming, which salespeople are driving the most profit, and where rising costs are eating into margins. This dashboard was built to bring all of that scattered data into one place so decisions on regional strategy, sales incentives, and cost control can be made with clear evidence instead of guesswork.

## Objective

The goal of this project is to give business stakeholders a clear, at-a-glance view of sales performance, shipment trends, and profitability across regions and salespeople, so they can identify what is driving revenue and where costs are cutting into margins.

## Key Metrics Tracked

- Total Sales: $10M, with a month-over-month view to catch dips early
- Total Boxes Shipped: 651K
- Total Shipments: 2K
- Total Costs: $4M
- Total Profit: $6M
- Overall performance score shown as a 61.2% gauge against target

## Dashboard Features

**Regional and product filtering**
Slicers on the left let users filter the entire dashboard by product category (Bars, Bites, Other) and by country (Australia, Canada, India, New Zealand, UK, USA), so the same report serves both global and regional views.

**Shipment trend over time**
A line chart tracks shipments by month from early 2023 through early 2024, making seasonal patterns and sudden drops easy to spot.

**Shipment distribution analysis**
A histogram breaks down individual shipment sizes, showing that most shipments cluster on the smaller end, with a long tail of larger ones.

**Salesperson performance table**
A ranked table lists every salesperson with their total sales, profit, profit percentage, and LBS percentage, along with a status indicator, making it easy to compare individual contribution and flag top or underperforming reps.

## Tools Used

- Power BI Desktop for data modeling, DAX measures, and report design
- Star schema data modeling for efficient filtering and aggregation
- DAX for calculated measures like profit percentage and month-over-month change

## Files in This Repository

- `Awesome_Chocolates_Dashboard.pbix` — the full Power BI project file
- `cocolate_sales_overview.png` — dashboard screenshot
- `README.md` — this file

## How to View

Since GitHub cannot render `.pbix` files directly, the screenshot above shows the finished dashboard. To interact with it live, download the `.pbix` file and open it in Power BI Desktop (free to install from Microsoft).

## Insights

Sales performance varies noticeably by region, and a small group of salespeople consistently drive higher profit percentages, suggesting an opportunity to study their approach and apply it more broadly across the team. The overall performance gauge at 61.2% also signals room to close the gap toward target.

##Screenshot

Show what the dhashboard looks like: 

Example : https://github.com/yamineerahangdale1-collab/Chocolate-dashboard-powerbi/blob/main/cocolate%20sales%20overview.png
