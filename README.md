# Superstore-Sales-PowerBI-SQl-Python

Power BI Analytics Dashboard
Overview
This Power BI dashboard turns four years of Superstore sales data into a clear executive summary. It helps sales leaders and product managers spot profit opportunities across regions, products, and customer segments using intuitive visuals and year-over-year comparisons.

 - <a href="https://github.com/ritikbh193/Data-Analysis-Dashboard/blob/main/Vrinda%20DataX2Analysis2.xlsx">Dataset</a>
![Superstore_PowerBI_Dashboard](https://github.com/user-attachments/assets/f9ff9f56-d609-4930-8e36-59c715a005dc)
Key Features
•	At-a-Glance KPIs: Shows sales, profit, and returns with year-over-year changes.
•	Trend Analysis: Tracks performance over time with a custom date setup.
•	Product measures: Highlights top and underperforming product categories.
•	Regional Breakdown: Maps profit by state to uncover geographic trends.
•	Customer Segments: Reveals sales distribution across customer types.
________________________________________
Business Problem & Solution
Problem
Superstore’s sales data holds valuable insights, but without visuals, it’s hard to:
•	Track performance trends quickly.
•	Spot profit drivers or losses.
•	See regional patterns.
•	Compare current results to past years.
Solution
•	Build a simple dashboard with key metrics and comparisons.
•	Analyze data by region, product, and customer type.
•	Find specific ways to boost profit.
•	Let stakeholders explore data easily.
Key Business Questions
How are core business metrics performing compared to prior periods?
Which products and regions drive profit or generate losses?
How do customer segments contribute to overall performance?
What patterns show up in regional profits?
Approach
1.	Prepared Data: Imported only essential columns for efficiency.
2.	Added Time Analysis: Created a custom date table for accurate year-over-year trends.
3.	Built Visuals: Designed a single-screen dashboard with clear, complementary charts.
4.	Mapped Regions: Added a map to show state-level profit patterns.
5.	Optimized Performance: Used efficient calculations for a fast, responsive experience.
This dashboard transforms raw data into a tool for spotting trends and making decisions.
________________________________________
Key Business Findings
Performance Overview
The dashboard shows strong growth in 2017 vs. 2016, with some areas needing attention.
Overall Growth:
•	Sales up 20.4% to $733K
•	Profit up 14.2% to $93K
•	Returns down 5.0% to 17.5%
 
Quarterly Trends:
•	Q1, Q3 and Q4 2017 beat prior year
•	November 2017 was the peak
•	Strong year-end suggests growth into 2018
 
________________________________________
Product Performance
Technology leads profits, but some products are losing money.
Technology Dominates Profitability
•	Tech profit up 27% vs PY to $50.68k
Top 3 Profit Makers:
1.	Copiers $25K
2.	Accessories $15.7K
3.	Phones $12,8K
Loss Makers:
•	Tables -$8.1K
•	Machines -$2,.9K
•	Supplies -$1.0
 
________________________________________
Regional Performance
Profit varies widely by state, revealing hidden challenges.
Top and Bottom States:
•	California leads with $29.4K profit
•	Texas**:** $8.8K loss
•	9 states unprofitable, including Illinois (-$6.7K)
 
Central Region Struggles
•	Sales flat (-0.2% vs PY)
•	Profit down 62.1% to $7.6K
•	Losses in Binders (-$4.0K) and Tables (-$2.2K) need action
 
Illinois Drill-Down
•	Sales up 15.8%, but profit still negative at -$6.7K (140.1% improvement)
•	High return rate (296%) hurts profitability, despite 145.8% improvement
 
Texas Drill-Down
•	Sales flat, profit improved 68% but still a $8.8K loss
•	Returns improved 62% to 180%, showing progress but ongoing issues
 
________________________________________
Customer Segments
Sales vary by customer type, with Home Office showing the most growth.
Sales Breakdown:
•	Consumer: 45.3%
•	Corporate : 33.9%
•	Home Office 21.8%
 
Home Office: Growth Leader
•	Sales up 51.5%
•	Profit up 40.3% to $21.1K
•	Returns down 29.2%
 
Corporate Challenges
•	Sales up 16.8% to $241.9K
•	Profit down 13.6% to $26.8K
•	Returns improved 10.1%, but margins need attention
 
________________________________________
Business Recommendations
Actionable Steps
1.	Grow Home Office Segment: Expand marketing to Home Office customers (51.5% sales growth, 40.3% profit growth).
2.	Focus on Technology: Prioritize Copiers ($25K) and Accessories ($15.7K); reduce focus on Tables (-$8.1K).
3.	Target Regional Issues: Support top states like California ($29.4K profit); address losses in Texas (-$8.8K) and Illinois (-$6.7K) with product adjustments or by modelling California’s processes.
4.	Review Corporate Margins: Review pricing in Corporate segment to reverse 13.6% profit decline despite sales growth.
5.	Leverage Peak Seasons: Plan for October-November spikes with inventory and marketing boosts.
Answers to Key Questions
1.	Performance vs. Last Year: 2017 sales up 20.4%, profit up 14.2%, returns down 5.0%.
2.	Profit Drivers and Losses: Technology (Copiers) drives profit; Tables and Machines lose money. California excels; Texas and Illinois struggle.
3.	Customer Segments: Home Office grows fastest; Corporate needs margin fixes.
4.	Regional Patterns: State-level differences (e.g., Central region) show local strategies matter more than regional ones.
These recommendations address specific performance issues while capitalizing on identified opportunities, providing a data-driven roadmap for improved business results.
________________________________________
Technical Implementation
Skills Demonstrated
•	Built advanced calculations for time trends and KPIs.
•	Created a custom date table for accurate analysis.
•	Designed an efficient data model with minimal columns.
•	Developed interactive visuals like a geo heatmap and charts.
•	Optimized for a fast, user-friendly experience.
What I Did
•	Data Setup: Imported Superstore data, keeping only necessary columns.
•	Time Analysis: Added a custom date table for year-over-year comparisons.
•	Calculations: Created measures for sales, profit, and returns, including % changes.
•	Visuals: Designed a compact dashboard with KPI cards, trends, and maps.
•	Interactivity: Added a slicer panel (accessible via funnel icon) to filter by date, region, and more. Enabled cross-filtering and drill-downs to instantly update all visuals when clicking on any chart.
Dataset
•	Tables Used: Orders (sales, profit, dates) and Returns (order IDs).
•	Key Measures: Sales, profit, return rates, and year-over-year changes.
Full project materials—including the Power BI file, cleaned dataset, and support files—are available in the GitHub repository.
For dataset structure and transformation notes, see the dataset_details.md file in the repo.
For DAX logic and calculated measures, see the dax_measures.md file in the GitHub repo.
Usage Tips
•	Use the funnel icon to open slicers and filter by date, region, or segment.
•	Hover over visuals for details.
•	Click segments to cross-filter the dashboard.
This setup turns raw data into a practical tool for business insights.
________________________________________
Conclusion
This Power BI dashboard turns Superstore sales data into clear, actionable measures. It shows I can:
•	Build efficient data models and calculations.
•	Create visuals that highlight trends and opportunities.
•	Deliver business recommendations that drive decisions.
It identifies profit gaps (e.g., Tables, Texas) and growth areas (e.g., Home Office, California), helping stakeholders make smarter choices.
Thanks for exploring!
________________________________________
Created by Tony Nick

