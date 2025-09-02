# Excel Dashboard
<p align="center">
  <img src="preview.png" width="45%" />
</p>
## About Data
This report provides a detailed analysis of the company's sales performance, leveraging data from both the "Orders" and "Sales Plan" sheets. The "Orders" sheet gives a granular, transactional view of the business, capturing key details about each sale, including geographic location, customer segment, and product specifics. The "Sales Plan" sheet, on the other hand, offers a strategic perspective by comparing actual sales against predetermined goals. Together, these two datasets provide a holistic view of the business, enabling both detailed operational insights and high-level strategic evaluation.
### Section 1: Analysis from the "Orders" Sheet
The "Orders" sheet serves as the foundation for understanding the day-to-day business operations. Each entry is a detailed record of a single sale, providing a wealth of information for a granular analysis.
-**Geographic Insights:** The data is broken down by City, State, and Region (Central, East, South, and West), which is crucial for evaluating market performance at a local level. For instance, a sale from Henderson, Kentucky, can be analyzed within the broader context of the South region's performance.
-**Customer and Product Segmentation:** Sales are categorized by Segment (Consumer, Corporate, Home Office) and products are classified by Category (e.g., Furniture, Office Supplies) and Sub-Category (e.g., Chairs, Binders). This allows for a precise analysis of who is buying and what is being sold, which is essential for targeted marketing and product development strategies.
-**Temporal Trends:** The inclusion of Order Date, Year, and Month allows for a time-series analysis to identify seasonal trends and peak sales periods. This can help in planning for future sales campaigns and managing inventory.
### Section 2: Analysis from the "Sales Plan" Sheet
The "Sales Plan" sheet provides the strategic context for the detailed "Orders" data. It is the primary tool for evaluating how well the company is meeting its goals.
-** Performance vs. Plan:** This sheet directly compares Sales with the Sales Plan on a yearly and regional basis. This side-by-side view is critical for evaluating the effectiveness of regional strategies and for identifying which areas are meeting, exceeding, or falling short of their targets.
-** Strategic Evaluation:** A significant variance between actual sales and the sales plan (as seen in some regions) indicates a need for a deeper investigation into the underlying factors. For example, a region consistently falling short of its plan may require a revised strategy or additional resources.
-** Accountability and Goal Setting:** This dataset is fundamental for management to assess regional and yearly performance. It provides the data needed to hold teams accountable and to set realistic yet ambitious goals for the future.
## Dashboard
### Overall Performance Metrics
-** Plan Achievement Rate:** This metric displays the overall percentage of sales achieved against the sales plan. This is shown in a rectangle round corner box.
-** Revenue Amount:** This shows the total sales revenue in Indian Rupees, broken down by region and year. This is displayed in a rectangle round corner box.
-** Quantity by Goods:** This displays the total quantity of goods sold, categorized by region and year. This is also displayed in a rectangle round corner box.
-** Number of Cities:** This shows the total number of cities included in the dataset for each region. This is displayed in a rectangle round corner box.
### Sales Analysis by Category and Segment
-** Sales by Category:** Yearly sales for the three main product categories are shown using a Column Chart. The percentage contribution of each category is displayed in a Doughnut Chart.
-** Sales by Segment:** Similar to the category analysis, yearly sales for the three customer segments are shown in a Column Chart, with a Doughnut Chart displaying the percentage breakdown.
-** Sales by Subcategory:** The top 8 highest-selling subcategories are highlighted in a Pie Chart.
### Geographic and Regional Performance
-** Revenue by Region:** A yearly breakdown of sales for all product categories, organized by region, is displayed in a Column Chart.
-** Positive Rate of Cities:** This section highlights the top 10 cities with the highest sales, shown in a Bar Chart and a rectangle shape box.
-** Negative Rate of Cities:** This section identifies the 10 cities with the lowest sales, which is displayed in a Bar Chart and a rectangle shape box.
-** Result Buttons:** The dashboard includes a "Best Result" button to show the positive rate and a "Worst Result" button to show the negative rate.
### Time-Based Performance
-** Revenue by Month: Monthly sales across all four years are displayed in a Bar Chart.
-** Revenues by Quarter:** This chart displays sales performance on a quarterly basis for all years using an Area Chart.
