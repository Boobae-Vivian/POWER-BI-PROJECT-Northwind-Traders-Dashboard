# NORTHWIND TRADERS DASHBOARD

## INTRODUCTION

In the ever-evolving realm of trading, the importance of well-informed decision-making cannot be overstated. Our mission is to empower traders with actionable insights and simplify their analytical workflows through the development of an advanced Tracking Dashboard. This dashboard is intricately designed, utilizing the extensive 'Northwind Traders' dataset, which encompasses seven diverse datasets, collectively painting a comprehensive picture of trading activities.

Our primary objective is to equip traders with a potent tool that transcends raw data, converting it into actionable intelligence. The Tracking Dashboard is geared towards providing a holistic perspective on key performance indicators (KPIs), crucial for strategic analysis and offering a thorough overview of trading performance. Beyond this, the dashboard aims to delve deeper into trading dynamics, uncovering insights such as identifying underperforming companies based on total quantity traded, spotlighting the top 5 countries ranked by total unit price, etc.

The Tracking Dashboard is a testament to our unwavering commitment to delivering a robust and user-friendly solution, fostering informed decision-making within the intricate landscape of trading.

## PROBLEM STATEMENT

1. Generate five (5) key performance indicators (KPIs) comprising:
   - Total Unit Price
   - Total Discount
   - Total Quantity
   - Total Freight
   - Average Delivery Duration

2. Identify and highlight companies with the lowest total quantity traded
3. Determine and showcase the top five(5) countries based on total unit price
4. Ascertain the total unit prices by category name
5. Highlight the top three (3) countries with the highest total quantity traded
6. Illustrate the distribution of total Freight costs by Employee Name
7. Integrate a dynamic "Year Slicer" for data filtering based on specific years.

This comprehensive outline aims to address key problem statements and guide the development of an effective tracking dashboard for traders using the 'Northwind Traders' dataset.

## SKILLS AND CONCEPTS DEMONSTRATED

In creating a tracking dashboard for traders using Power BI with the 'Northwind Traders' dataset, several skills and concepts need to be demonstrated. Here is a breakdown of the essential skills and concepts:

- Data Import and Transformation
- Data Modeling
- Visualization Techniques
- KPI Creation Utilizing DAX (Data Analysis Expressions)
- Data Aggregation and Calculation
- Hierarchical Analysis: Demonstrate the ability to analyze data hierarchically, such as by category name or employee name
- Dashboard Interaction: Implement interactive features like slicers, filters, and drill-through actions to enhance user control.
- Documentation and Presentation

By effectively demonstrating these skills and concepts, the Power BI dashboard will serve as a powerful tool for traders, providing actionable insights and facilitating informed decision-making in the trading domain.

## DEVELOPING THE NORTHWIND TRADERS DASHBOARD: STEPS, ANALYSIS, AND DISCUSSIONS

- Step 1 - Data Importation:
  ---

  Import the 'Northwind Traders' dataset, consisting of seven distinct datasets, into Power BI Desktop by adhering to the prescribed steps outlined in my work titled "Power BI Task 1: Data Integration".[Access the document here](https://github.com/Boobae-Vivian/POWER-BI-TASK-1-Dataset-Integration). As a result of this process, you will observe the presence of seven(7) datasets—categories, customers, employees, order_details, orders, products, and shippers—in the data pane within the Power BI environment. These datasets will be highlighted by a yellow line, as depicted in the snapshot below.

- Step 2 - Data Cleaning and Transformation:
  ---

  Kindly note that the imported datasets underwent data cleaning; however, unfortunately, snapshots were not taken during the cleaning process of the seven datasets. Nevertheless, it's important to note that a separate task focused on data cleaning, using an employee CSV dataset, has been completed. This task is extensively documented in my work on data cleaning and transformation, specifically detailed in Power BI Task 2. [View Here](https://github.com/Boobae-Vivian/POWER-BI-TASK-2-Data-Cleaning)

- Step 3 - Data Modelling:
  ---

  Data modeling stands out as a key functionality within the Power BI tool, facilitating the linkage of multiple data sources through the establishment of relationships. These relationships define the connections between various data sources, and our objective is to construct a robust data model that effectively captures the interconnections among the seven distinct datasets within 'Northwind Traders.' Our aim is to create suitable relationships between tables, ensuring a seamless foundation for data analysis.

  In this context, the predominant relationship type is the "one-to-many" relationship. This type of relationship establishes a connection where one record in a table corresponds to multiple related records in another table. To achieve this, navigate to the model view icon on the left side of the Power BI environment. Typically, Power BI automatically detects and creates relationships. However, if these relationships are not automatically established, one can manually create them by linking or dragging a common column in one table to meet another common column in a different table.

  In my case, Power BI automatically created these relationships, but the initial arrangement was not intuitive. Therefore, I invested additional effort to reorganize the relationships, enhancing readability and understanding. The outcome of this rearrangement is presented in the snapshot provided in the output of step 3 below. Notably, the asterisk (*) in the snapshot denotes "many", indicating a one-to-many relationship.

  STEP 1,  STEP 2  and  STEP 3
  :-----------------------------:
  ![](PowerBI.png)

   OUTPUT OF STEP 3
  :-----------------------:
  ![](PowerBI1.png)

- Step 4 - Canvas Background and Dashboard Name:
  ---

  To commence the dashboard development after modeling datasets and establishing relationships between tables, proceed by clicking on the report view icon situated on the left side of the Power BI environment. Upon navigating back to the canvas page, prior to selecting a visual to appear in the report canvas and dragging fields from the datapane into the visualization pane, the canvas is first edited by applying a green background color.

  To achieve this, access the visualization pane and click on the format page icon. Choose the canvas background option and select the green color for the background.

  Subsequently, provide a fitting name for the dashboard by inserting a textbox and typing in "**NORTHWIND TRADERS DASHBOARD**". Following this, further refine the appearance of the name by editing it to be suitable for a dashboard title. In my case, I enhanced the name by adding shapes to make it stand out, giving the shapes a black background. These adjustments can be made using the format page settings in the visualization pane.

- 













































