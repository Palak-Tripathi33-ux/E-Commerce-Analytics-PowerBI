# E-Commerce-Analytics-PowerBI
Developed a dynamic Power BI dashboard analyzing 161K in revenue, 2K in quantity sold, and 26K in net profit. Features comprehensive data models tracking customer behavior (44% COD preference, 63% Clothing sales dominance) and regional performance across major states like Maharashtra to deliver actionable business insights for stakeholders.

📊 E-Commerce Sales Dashboard — Power BI
> An interactive, dark-mode Power BI dashboard tracking e-commerce revenue, profitability, and regional performance to support faster business decisions.
---
📁 Project Overview
Built a single-page Power BI dashboard that consolidates transactional e-commerce data into an executive-ready reporting view. The report connects an `Orders` table (customer, state, date) with a `Details` table (category, amount, quantity, profit, payment mode) and surfaces insights through 10+ interactive visuals.

🎯 Business Objective
Turn raw sales transactions into a self-service analytics tool so stakeholders can monitor KPIs, spot regional gaps, and understand product-level profitability — without writing a single query.

🧩 Dashboard Features
The dashboard opens with four KPI cards surfacing the most critical numbers at a glance — Total Revenue, Quantity Sold, Total Profit, and Average Delivery Value (ADV). Below that, a monthly profit trend column chart tracks how margins move across the year, making seasonality easy to spot. A sub-category profit bar chart ranks every product line by profitability, immediately separating what's driving margin from what's dragging it. Two donut charts handle composition — one showing order volume split by product category, the other breaking down payment preferences across COD, UPI, Card, and EMI. A state-wise revenue bar chart compares performance across Indian states, while a top customers column chart identifies the highest-spending individuals for CRM targeting. Finally, Quarter and State slicers sit at the top of the report, cross-filtering every visual simultaneously so stakeholders can drill into any time period or region without touching the underlying data.

🛠️ Tools Used
Power BI Desktop 2025.11 · DAX · Power Query (M) · Custom JSON Theme

💡 Key Insights
Profit is unevenly distributed across sub-categories — a few carry the margin, others drag it down
COD remains a dominant payment mode, carrying higher return and operational risk
Revenue is concentrated in select states, pointing to clear expansion opportunities
Monthly profit fluctuates noticeably, suggesting seasonal or promotional dependencies

📚 Learning Outcomes
Strengthened DAX skills, particularly around filter context and slicer-aware measures
Learned to model relationships between fact and dimension tables without many-to-many pitfalls
Practiced visual sequencing — KPIs → trends → breakdowns — for a logical reading flow

⚠️ Challenges Faced
Resolving DAX measure errors when slicers were applied required deep-diving into filter context behavior
Maintaining text legibility across a dark-gradient theme needed manual color overrides per visual type
Configuring cross-filter interactions between two slicers without creating circular dependencies

🙋 My Contributions
Independently handled the full pipeline — data cleaning, model design, DAX measures, visual selection, theme customization, and layout polish. 
Every element in the report reflects a deliberate decision, not a default.

🧠 Skills Demonstrated
`Power BI` · `DAX` · `Power Query` · `Data Modeling` · `KPI Design` · `Business Intelligence` · `E-Commerce Analytics` · `Dashboard UX` · `Data Storytelling`

✅ Conclusion
This project demonstrates the ability to take raw transactional data and deliver a dashboard that a business team can actually use — accurate, interactive, and designed with the decision-maker in mind.
