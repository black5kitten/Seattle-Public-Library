## Seattle Public Library Checkout Analytics Dashboard (Power BI)

### Overview
Interactive Power BI dashboard analyzing 12 years (2005–2017) of checkout patterns from Seattle Public Library, covering physical items (books, DVDs, CDs, etc.) across 729K total items in inventory and 92M total checkouts. The dashboard helps visualize circulation trends, item popularity, and inventory management insights.

### Dashboard Pages
1. Inventory Management
KPI cards: Total locations (32), total items in inventory (729K), items never checked out (126K), average publication year, floating vs non-floating items.
​

Bubble chart showing relationship between inventory size, checkout volume, and item type (e.g., Book: Adult/YA, DVD: Adult/YA, CD: Adult/YA).
​

Bar charts comparing total items in inventory by item type.
​

### 2. Item Popularity
Most popular item type (Book: Adult/YA), total unique titles (567K), unique authors (218K), and total item types (79).
​

Top authors by checkout volume (Seuss, Willems, Meadows, Osborne, Rylant).
​

Top titles by checkout count and first author.
​

Time series showing checkout trends by item type (2004–2018), with peak activity around 2009.
​

Treemap visualizing checkout distribution by collection description (NA-DVD Fiction, NA-Compact Discs, NA-Fiction, etc.).
​

### 3. Checkout Trends
KPI cards: Total checkouts (92M), average checkouts per day (19.37K), peak year (2009), peak year checkouts (9M).
​

Monthly checkout time series (2005–2017) showing growth, peak, and decline patterns.
​

Year-over-year growth percentage analysis.
​

Checkout patterns by day of week (highest: Saturday, Wednesday, Tuesday).
​

Checkout patterns by hour (peak usage: 12–3 PM).
​

Monthly checkout distribution across the year.
​

### Data & Processing
Data source: Seattle Public Library Checkout Records (Kaggle) | License: Public Domain 

Period: April 2005 – September 2017
​

Note: This is a portfolio project using publicly available data; not affiliated with Seattle Public Library.
​

### Workflow: Data cleaning and exploratory data analysis (EDA) in Python (Pandas, NumPy); additional transformations in Excel; dashboard design and DAX measures in Power BI.

### Tools & Technologies
Python (Pandas, NumPy)

Microsoft Excel

Power BI (Power Query, DAX)

### Key Insights Demonstrated
Ability to handle large-scale circulation data (92M records) and extract actionable patterns.
​

Time-series analysis revealing usage peaks, seasonal trends, and long-term circulation decline.

Multi-dimensional analysis linking inventory characteristics (item type, collection, author) to checkout behavior.

User behavior profiling by hour, day of week, and month to optimize staffing and collection management.
​
### Screenshot
Example: ![Dashboard Preview](https://github.com/black5kitten/Seattle-Public-Library/blob/main/seattle_library.png)

Author: Akancha Kesarwani

Power BI Developer | Data Analyst | Software Developer

