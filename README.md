## PIZZA SALES PERFORMANCE DASHBOARD | EXCEL, SQL ##
An interactive, single-page Excel dashboard that transforms raw pizza sales transaction data into actionable business intelligence — covering revenue trends, order behavior, product performance, and time-based demand patterns.

📌 Project Overview

This project analyzes a full year of pizza restaurant sales data and consolidates it into a single, decision-ready dashboard. The goal was to give a restaurant owner or operations manager a at-a-glance view of overall performance — without needing to dig through raw spreadsheets — so they can make faster, data-backed decisions on staffing, inventory, and menu strategy.

To ensure the dashboard's numbers were accurate and trustworthy, every key metric was independently re-calculated using MySQL queries run directly against the raw dataset and cross-checked against the Excel outputs — treating this as a mini data-validation / QA exercise rather than a single-tool project.

❓ Problem Statement

Restaurant operations generate large volumes of order-level data, but this raw data is rarely usable in its native form. Management typically struggles to answer basic but critical questions such as:


Which days and hours see the highest customer demand?
Which pizza categories and sizes actually drive revenue?
Which menu items are top performers, and which are underperforming and worth reconsidering?
How is order volume distributed across the week and across the day?


Without a consolidated view, these insights stay buried in transactional data, leading to reactive rather than proactive decision-making around staffing, inventory planning, and menu design.

🎯 Objective

To design a dynamic Excel dashboard that:


1. Summarizes key performance indicators (KPIs) in one view.
2. Identifies peak business hours and days to optimize staff scheduling.
3. Breaks down sales by pizza category and size to guide inventory and pricing decisions.
4. Highlights best- and worst-selling menu items to support menu engineering decisions.
5. Allows filtering by month/period for time-based trend analysis.

🧰 Tools & Techniques Used

Microsoft Excel
MySQL
Pivot Tables & Pivot Charts
Slicers / Timeline Filter
Formulas (SUMIFS, COUNTIFS, AVERAGEIFS, etc.)
SQL Aggregate Functions & GROUP BY

Key Insights

1. Peak Days: Order volume is highest on Friday and Saturday evenings, with Friday alone crossing 3,500+ orders.
2. Peak Hours: Two clear demand spikes emerge — the 12 PM–1 PM lunch rush and the 4 PM–8 PM dinner rush — both visualized through an hourly trend line.
3. Category Performance: The Classic category contributes the maximum share of total sales and orders, followed closely by Supreme and Veggie.
4. Size Preference: Regular-sized pizzas dominate sales (~46%), while X-Large is a negligible contributor — a strong signal for inventory and portioning decisions.
5. Best Sellers: The Classic Deluxe and The Barbecue Chicken pizzas are the top revenue and volume drivers.
6. Underperformers: The Brie Carre Pizza ranks lowest in both orders and revenue — a candidate for menu review or promotional repositioning.
7. Time Intelligence: A built-in month/period slicer (Jan–Jun and beyond) allows the dashboard to be filtered dynamically for period-specific analysis.


   <img width="1155" height="655" alt="Screenshot of pizza" src="https://github.com/user-attachments/assets/9b51697b-8f89-4913-8486-b46f737b7e1a" />






