# 📊 Deep Insights Report – Adidas Sales Dashboard (2020–2021)

## 1. Introduction

This report provides a comprehensive business analysis of Adidas US sales data for the years 2020 and 2021. The project focuses on uncovering insights through a Power BI dashboard, allowing users to filter data by product, region, retailer, and sales method. The goal is to communicate data-driven insights that inform strategic decisions in marketing, operations, and product development.

## 2. Objectives

The key objectives of this project include:

* To analyze Adidas product sales trends across two years
* To evaluate regional, state-level, and retailer-specific performance
* To assess the impact of pricing and profit margins on total revenue
* To build a dynamic Power BI dashboard for data storytelling
* To identify strategic opportunities and improvement areas for Adidas

## 3. Data Overview

### Adidas US Dataset

The dataset used in this project includes transactional sales data, product categories, and regional location keys. It contains over 9,000 records detailing:

* Invoice dates, product types, sales methods (in-store, outlet, online)
* Retailers such as Foot Locker, Amazon, Walmart
* Units sold, total sales, profit, and operating margins

## 4. Data Preparation

Data was prepared in **Power Query** and refined using **DAX** formulas in Power BI.

### Key Preparation Steps

* Removed non-data headers and blank rows
* Extracted year and month from invoice dates
* Converted financial fields (e.g., Sales, Profit) to numeric format
* Created a separate **Date Table** for proper time intelligence and period comparisons
* Used DAX to calculate KPIs: Year-over-Year (YoY), Month-over-Month (MoM) changes, profit margins

## 5. Business Insights

📌 These insights reflect data storytelling based on the visual dashboard:

* 🥇 **Top Region**: The West leads with \$270M+ in sales and 2.4K transactions, suggesting stronger retail penetration or brand loyalty.
* 🛍️ **Sales Method**: In-store purchases contributed most to revenue, despite the rise in online shopping.
* 👟 **Top Product**: Men's Street Footwear was the highest revenue generator, followed closely by Women's Street Footwear.
* 🏪 **Top Retailer**: West Gear and Foot Locker drove the majority of sales, while Amazon and Walmart trailed behind.
* 📈 **Standout State**: California showed a 590% YoY sales growth, significantly above all other states potentially due to regional marketing or events.
* ⚠️ **Flat Growth Areas**: Washington and Colorado showed 0% growth, marking them as potential focus areas for strategy improvements.
* 💰 **High Transaction Volume**: 10K+ transactions with \$899M in total sales reflect a solid average spend (\~\$90 per transaction).
* 📊 **Online Sales**: Online methods increased in 2021 but still lag behind in-store performance, highlighting a digital growth opportunity.
* 💹 **Operating Margin**: Most profitable transactions were linked to mid-range priced items with high unit volume.
* 🕐 **Sales Spikes**: July and December marked seasonal highs, likely driven by summer gear and holiday demand.

These dashboard-driven insights serve as a foundation for data-backed decisions across Adidas sales and marketing strategies.

## 6. Strategic Recommendations

* **Double down on high-performing regions** like the West with expanded retail partnerships.
* **Promote online-exclusive collections** to boost digital channel engagement.
* **Launch marketing campaigns** in low-growth states to uncover new opportunities.
* **Focus on pricing strategy**  maintain mid-range product pricing to drive conversions.
* **Align product launches** with high-sales months (July, December) to maximize impact.

## 7. Acknowledgment

This project was completed as part of the **Mentorship Data Analytics – Deep Dive** training program. Special thanks to my tutor, who provided guidance throughout the dashboard creation process from data modeling in Power Query to DAX-based analysis and insight storytelling.

## 8. Conclusion

This report illustrates how structured sales data and thoughtful dashboard design can yield powerful business insights. The project not only visualizes Adidas performance but also identifies clear strategic actions to optimize sales, customer engagement, and operational efficiency.
