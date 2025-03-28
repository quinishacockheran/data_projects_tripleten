--------------------
README: Restaurant Analysis for Zomato Project
--------------------

Project Overview:
-----------------
This project analyzes the performance of restaurants listed on Zomato by evaluating key metrics such as popularity (measured by rating counts) and revenue generation. The analysis uncovers patterns and correlations between customer reviews and financial performance, identifies top-performing segments, and provides actionable recommendations for business improvement.

Project Components:
-------------------
1. Data Files:  
**Zomato Data:** (Note: Due to file size restrictions, this data is not included in the file.)
   - Restaurant.csv: Contains restaurant details including restaurant_id, name, city, rating, rating_count, cost, cuisine, lic_no, link, address, and menu link.
   - Orders.csv: Contains order records including order_date, sales_qty, sales_amount, currency, user_id, and restaurant_id.
   - Menu.csv: Contains menu details including menu_id, restaurant_id, food_id, cuisine, and price.
   - Food.csv: Contains food item details including food_id, item, and veg_or_non_veg.
   - Note: The Users table was excluded as it was not relevant for this analysis.

2. Visualizations:
   - A screenshot showing the relationships between the tables.
   - Additional pdf capturing key visualizations, including bar charts, scatter plots, and treemaps.

3. Final Report:
   - Provided as a PDF document containing the complete analysis, methodology, visualizations, key findings, conclusions, and recommendations.

4. Power BI File: (Note: Due to file size restrictions, this data is not included in the file.)
   - The Power BI Desktop file (.pbix) is not included in this submission due to file size restrictions.

Methodology:
------------
1. Data Cleaning and Preparation:
   - Validated data types (numerical, text, and date fields).
   - Handled missing values and removed duplicates from critical fields.
   - Standardized text fields (e.g., city names and cuisine types) using functions like TRIM and case conversion.
   - Established one-to-many relationships between:
       • Restaurant and Orders tables (via restaurant_id).
       • Restaurant and Menu tables (via restaurant_id).
       • Food and Menu tables (via food_id).

2. Exploratory Analysis:
   - Visualizations Developed:
       • Top 5 Most Popular Restaurants (by rating count) – Bar Chart.
       • Top 5 Restaurants by Revenue – Bar Chart.
       • Popularity vs. Revenue Comparison – Scatter Plot.
       • Price Distribution by Cuisine – Treemap.
       • Revenue Distribution by Cuisine – Treemap.
   - Note: A geospatial analysis using built-in geocoding was considered but excluded due to complexity.

Key Findings & Recommendations:
-------------------------------
- A significant alignment exists between restaurants with high rating counts and those generating high revenue, though discrepancies indicate additional factors (such as pricing strategy and location) influencing revenue.
- Certain cuisines are major revenue contributors, suggesting targeted opportunities for strategic investments.
- Recommendations include focusing on strategic investments, optimizing menu pricing, and continuously monitoring key performance indicators (KPIs).

How to Use the Project Files:
-----------------------------
- Open the Final Report PDF to review the detailed analysis, methodology, visualizations, key findings, conclusions, and recommendations.
- Refer to the screenshot showing table relationships to understand how the data tables are connected.
- Additional pdf of the visualizations illustrate the key insights derived from the analysis.

Contact Information:
--------------------
Project Lead: Quinisha Cockheran
LinkedIn: www.linkedin.com/in/quinisha-cockheran

--------------------
End of README
--------------------