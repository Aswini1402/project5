# project5

# Summary of US Regional Sales Dataset Analysis
# Overview

Dataset size: 7,991 records with 16 columns, covering U.S. regional sales transactions.

Data scope: Includes order details, sales channels, warehouses, product info, pricing, and discount data.

Currency: All transactions are recorded in USD.

# Key Findings
# Temporal Trends

Records span multiple years (e.g., 2018–2020) with daily entries.

Key date fields: ProcuredDate, OrderDate, ShipDate, DeliveryDate, enabling end-to-end supply chain timeline analysis.

Repeated customer, store, and product IDs allow longitudinal tracking.

# Sales & Order Behavior

Order Quantity: Average of ~4.5 units per order, with both small and bulk orders represented.

Unit Price: Wide variation — from low-cost items to premium products over $1,000/unit.

Discounts: Applied on ~11.5% of orders (mean discount rate ~0.12).

# Regional & Channel Distribution

Sales Channels: 4 categories (e.g., In-Store is most frequent with ~3,300+ orders).

Warehouses: 6 distribution centers, with some handling 2,500+ orders individually.

Customer/Store IDs: Broad distribution indicates diverse customer base and multiple store locations.

# Financial Indicators

Unit Cost vs. Unit Price: Clear margin data available for profitability analysis.

Currency: Consistent (USD) — no currency conversion issues.

High-value products: Over 5,000 unique product cost entries, suggesting varied product catalog.

# Data Completeness & Quality

No missing values across all 16 columns.

Dates, IDs, and numeric fields are clean and consistent.

Each order number is unique, ensuring transaction-level granularity.

# Conclusion

The dataset provides a comprehensive view of U.S. regional sales activity, including order patterns, pricing, discounts, and supply chain timing.

# Enables analysis of:

Regional sales performance and warehouse efficiency.

Profit margins and discount effectiveness.

Customer and product-level trends over time.

# Balanced insights:

Data spans multiple years, sales channels, and warehouse regions.

Includes both high-value and low-cost products, enabling diverse market analysis.

# Future analysis could involve:

Time-series forecasting for demand planning.

Margin optimization using pricing and discount data.

Customer segmentation based on repeat purchase behavior.

Supply chain performance using order-to-delivery timelines.
