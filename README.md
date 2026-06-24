# E-Commerce Sales Dashboard (Power BI)

## Project Overview

This project features an end-to-end interactive E-Commerce Sales Dashboard engineered using Microsoft Power BI to analyze comprehensive sales performance, customer purchasing behavior, and organizational profitability across multiple Indian states and product lines. 

The architecture consists of a single-page, fully interactive business intelligence interface that processes 12 months of transaction history. 

It tracks 4 core KPIs—Total Amount (**438K**), Quantity Sold (**6K**), Profit (**37K**), and Average Order Value (**AOV: 121K**)—designed specifically to empower corporate stakeholders to make quick, data-backed operational decisions without navigating complex, raw spreadsheets.

## Business Objective

The strategic objectives of this deployment were to diagnose retail operations and drive immediate margin optimization by:

* Identifying high-performing geographic states, product categories, and key accounts driving the largest share of revenue.

* Understanding localized customer payment method preferences to optimize check-out funnels and lower transaction processing costs.

* Pinpointing exact periods of negative profitability to investigate seasonal baseline variations and discount campaign over-exposure.

* Evaluating granular sub-category profitability margins to direct inventory management, supply chain positioning, and targeted marketing spend.

## Dashboard Features

* **Executive KPI Cards:** High-visibility metrics displaying Amount (**438K**), Quantity (**6K**), Profit (**37K**), and AOV (**121K**) pinned to the top focal point for instant performance indexing.

* **Monthly Profit Trajectory Analysis:** A time-series bar chart diagnosing month-by-month margin health, exposing critical profit dips and deficit baselines during the June and July cycles.

* **Payment Mode Allocation:** A diagnostic donut chart mapping consumer settlement preferences: COD (**44%**), UPI (**21%**), Debit Card (**13%**), Credit Card (**12%**), and EMI (**10%**).

* **Geographic Revenue Distribution:** A horizontal ranking chart evaluating Sum of Amount across regional markets, isolating Maharashtra and Madhya Pradesh as primary growth engines.

* **Key Account Identifier:** A behavioral profile chart monitoring the Sum of Amount by Customer Name to distinguish top-tier whale accounts (**Harivansh, Madhav, Madan Mohan, and Shiva**).

* **Category Volume Share:** A volume-based donut chart analyzing product category velocity, highlighting Clothing as the volume anchor at **63%**, followed by Electronics (**21%**) and Furniture (**17%**).

* **Granular Sub-Category Profit Matrix:** An analytical chart measuring sub-category profitability, pinpointing Printers and Bookcases as highest margin contributors (approaching **10K** each).

* **Drilldown Filter Slices:** Integrated Quarter Filters (Q1–Q4) paired with a dynamic State Slicer to facilitate frictionless cross-filtering and multi-dimensional analysis.

## Tools & Technical Stack Used

* **Microsoft Power BI Desktop:** Core platform used for semantic modeling, visual layout design, interface architecture, and cross-report interaction.

* **Microsoft Excel:** Utilized for source database storage, initial tabular structuring, and schema preparation.

* **DAX (Data Analysis Expressions):** Authored custom analytics measures to compute multi-variable KPIs, Profitability ratios, AOV formulas, and Year-To-Date (YTD) comparisons.

* **Power Query Editor:** Conducted deep ETL workflows, covering schema type conversions, structural data transformations, text normalization, and attribute standardization.

## Key Insights

* **Digital Trust Deficit:** Cash on Delivery (COD) dominates customer preference at **44%**, signifying a pronounced reliance on physical currency over digital alternatives. Introducing target-specific cashback or loyalty incentives for digital nodes (UPI/Cards) could migrate consumers up the value chain.

* **Volume vs. Value Disparity:** The Clothing category drives an impressive **63%** of total transaction quantity, yet presents significantly tighter margin thresholds compared to low-volume, high-margin divisions like Electronics and Printers.

* **Regional Revenue Anchor:** Maharashtra represents the single most critical regional asset, generating a gross transaction volume nearly double that of the capital territory, Delhi.

* **Deficit Period Diagnosis:** Operational margins experience sudden deceleration during the June and July windows, resulting in near-zero or negative net profitability. This dip points to localized post-Q1 discount exhaustion, seasonal shifts, or unoptimized return volumes.

* **High-Margin Sub-Categories:** Printers and Bookcases stand out as portfolio anchors, yielding outsized net profit figures approaching **₹10K** each.

* **High-Value Customer Retention:** Core consumers—Harivansh, Madhav, Madan Mohan, and Shiva—individually outpace **₹5K** in gross order amounts, qualifying them as high-priority profiles for targeted retention and loyalty campaigns.

* **Festive Season Elasticity:** Q4 (October–December) records a substantial, sharp profit acceleration, driven by festive shopping demands across all primary demographics.

## Learning Outcomes

* **End-to-End BI Architecture:** Mastered the foundational process of constructing a production-ready Power BI report from completely raw data streams up to final visual compilation.

* **Advanced Measure Design:** Developed an explicit understanding of context-aware DAX evaluation mechanics vs. calculated row columns, optimizing calculation speeds and scalability.

* **Relational Interface Engineering:** Practiced structuring complex cross-filtering and synchronized slicer hierarchies to maintain absolute alignment across different visual modules.

* **Visual Storytelling & Chart Selection:** Gained expertise in selecting the mathematically correct chart type for specific information architectures (e.g., donut visuals for parts-to-whole share, combo graphs for value/volume vectors, and grouped bars for categorical ranking).

* **Executive Design & UI/UX Principles:** Mastered the use of corporate color schemes, contrast management, grid boundaries, and card structures to maximize cognitive clarity for executive viewers.

## Challenges Faced & Resolution

* **Structural Inconsistencies in Source Data:** Raw data sheets suffered from mismatched chronological date strings and extensive unmapped regional text variables.

  * *Resolution:* Developed a rigorous transformation recipe within Power Query to standardize data models and enforce type-safety constraints before the modeling stage.
  
* **Deconstructing Multi-Variant Profit Loss:** Isolating the root cause of negative profitability cycles during mid-year months was obscured by aggregate values.

  * *Resolution:* Configured deep cross-filtering pathways to dissect transaction records concurrently by product type and settlement option, exposing hidden revenue leaks.
  
* **Average Order Value (AOV) Mathematical Bias:** Calculating AOV using simplistic column averages yielded skewed statistical figures due to varying line quantities.

  * *Resolution:* Engineered a robust DAX division measure leveraging unique transaction counters to isolate true operational order value baselines.
  
* **Visual Clutter & Space Conservation:** Arranging 7+ heavily informative data components onto a single view field initially threatened visual clarity and user experience.

  * *Resolution:* Executed multiple layout revisions, refined text parameters, removed non-essential grid markings, and implemented an optimized grid template to maintain professional whitespace.

## My Efforts and Contributions

* Audited, normalized, and modeled raw e-commerce transactional database pools completely independently.

* Conceived and drafted the entire multi-visual grid structure from an initial blank layout canvas without relying on standard pre-built workspace templates.

* Programmed the custom DAX calculation library, including parameters for Profit Margins, unique order ADV metrics, and conditional filtering variables.

* Enforced an intentional corporate visual identity utilizing a dark purple backdrop accented by white content cards to ensure executive-grade readability.

* Validated cross-filtering boundaries and dependency connections across all elements to protect interactive data integrity.

* Restructured traditional date-filtering mechanisms by constructing dedicated quarter buttons (Q1–Q4) for a faster, user-friendly navigation flow.

## Skills Demonstrated

`Business Intelligence (BI)` • `Data Visualization` • `DAX Calculation Engineering` • `Power Query & ETL` • `Data Optimization & Cleansing` • `Market Segmentation` • `Financial Performance Analytics` • `Dashboard UI/UX Layout Design`

## Conclusion

This portfolio project demonstrates my capacity to ingest raw commercial transactional datasets, manage structural information clean-ups, establish semantic models, and deploy interactive reporting tools that deliver actionable business value. 

As a BBA student expanding into advanced analytics and operations tracking, this project showcases my ability to blend high-level business administration frameworks with modern data intelligence infrastructure to solve real-world margin challenges.

***

**Project Developed By:** Palak Tripathi | BBA Student | Aspiring Data & Business Analyst  

**Let's Connect:** Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/palak-tripathi-37a56234a/) or reach out if you would like to discuss this project further!
