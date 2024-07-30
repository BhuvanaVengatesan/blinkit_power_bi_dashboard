# Blinkit Sales Analyze
## Objective:
Blinkit wants to enhance business success by leveraging data analysis techniques, particularly to conduct a comprehensive  analysis of sales performance, customer satisfaction and  inventory distribution using  various KPIs and
visualization in Power BI.
## Areas I Worked on:
1) Data Cleaning
2) Dax Queries
3) Data Visualization
4) Final insights

## Steps Undertaken:
1) **Data Cleaning**:
        The process includes applying filters to eliminate null, removing duplicates, rectifying typing errors, validating date formats.
2) **DAX Measure**:
        By employing the DAX measure "Total sales = SUM('BlinkIT Grocery Data'[Sales])", "Avg sales = AVERAGE('BlinkIT Grocery Data'[Sales])", "No of Items = COUNTROWS('BlinkIT Grocery Data')", "Avg of rating = AVERAGE('BlinkIT Grocery Data'[Rating])",
 created new parameter to get metrics called "Metrics = {
    ("Total Sales", NAMEOF('BlinkIT Grocery Data'[Total sales]), 0),
    ("Avg Sales", NAMEOF('BlinkIT Grocery Data'[Avg sales]), 1),
    ("No of Items", NAMEOF('BlinkIT Grocery Data'[No of Items]), 2),
    ("Avg Rating", NAMEOF('BlinkIT Grocery Data'[Avg of rating]), 3)
     }".

3) **Data Visualization**:
        Generated visualizations to analyze and showcase total sales, average sales, number of items sold, average rating, sales based on fat content, outlets size, outlet location and segments using horizontal bar charts, line charts, pie charts and funnel chart.

4) **Final Insights**:
* Low fat content demonstrates the highest sales, reflecting a consistent demand for products within this category.
* The data shows a highest sales figures for tier 3 outlets, suggesting a stronger market presence and customer engagement in these areas. 
*   Fruits and vegetables, snack foods, and household items have the highest sales. This indicates a strong consumer preference and consistent demand for these categories.
*  Medium-sized outlets are experiencing higher sales figures, which suggests a more efficient use of space, better customer reach. This trend highlights the need to re-evaluate the strategies employed in high-sized outlets, as optimizing their operations could potentially increase their sales performance.
* Supermarket Type 1 boasts a high number of items sold and exceptional item visibility.
* The success of Supermarket Type 1 highlights the importance of strategic inventory management and marketing efforts that could be replicated across other supermarket types to enhance overall performance.

