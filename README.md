# Blinkit Sales Analysis using Python

## Objective
To conduct a detailed analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution using key performance indicators and data visualizations. The analysis aims to uncover actionable insights and identify optimization opportunities in product offerings and outlet strategy.

## Dataset
Blinkit Analysis - <a href="https://github.com/Simran1028/Blinkit-Analysis/blob/main/blinkit_data.csv">Dataset</a>

## KPI Requirements
The following key performance indicators were used for analysis:
- Total Sales: The overall revenue generated from all items sold.
- Average Sales: The average revenue per item sold.
- Number of Items: The total count of different items sold.
- Average Rating: The average customer rating for items sold.

## Chart Requirements
- Total Sales by Fat Content : Analyze the impact of fat content on total sales.
- Total Sales by Item Type : Identify the performance of different item types.
- Fat Content by Outlet for Total Sales : Compare fat content performance across different outlet types.
- Total Sales by Outlet Establishment Year : Evaluate how the age of an outlet influences sales.
- Sales by Outlet Size : Analyze the correlation between outlet size and total sales.
- Sales by Outlet Location : Assess geographic distribution of sales across locations.

## Process
- Data Cleaning: Removed nulls, encoded categorical data, and normalized formats.
- KPI Calculation: Computed total and average metrics using grouped dataframes.
- Visualization: Used Python libraries (matplotlib, seaborn) to create charts.
- Insight Extraction: Evaluated each visualization to derive strategic takeaways.

## Project Insights
- Total Sales by Fat Content (Pie Chart)
  - Regular fat content products dominate total sales.
  - Low fat options lag behind, though preferred slightly more in Tier 1 outlets.
 ![Screenshot 2025-04-24 033425](https://github.com/user-attachments/assets/36144a5b-d76c-4842-b8d8-4d7f020d1af3)



- Total Sales by Item Type (Bar Chart)
  - Snacks, Fruits & Vegetables, and Dairy items have the highest sales.
  - High correlation between frequent consumption and high sales.
 ![Screenshot 2025-04-24 033440](https://github.com/user-attachments/assets/d6e54ae5-bd8f-4a9f-a206-b4a0fadce524)


- Fat Content by Outlet Tier (Stacked Column Chart)
  - Tier 1 locations show a slight preference for Low Fat options.
  - Regular fat content is preferred across all tiers.
 ![Screenshot 2025-04-24 033450](https://github.com/user-attachments/assets/d03e8c67-78fd-47be-9026-ec118fbfe713)


- Total Sales by Outlet Establishment Year (Line Chart)
  - Outlets established earlier (before 2000) show consistent, higher sales.
  - Newer outlets show promise but need more time or better positioning.
 ![Screenshot 2025-04-24 033502](https://github.com/user-attachments/assets/e2203f64-5602-4d0a-922e-b016642fe9bb)


- Sales by Outlet Size (Pie Chart)
  - Medium-sized outlets generate the majority of sales.
  - High-end outlets have smaller share, likely due to exclusivity or location factors.
 ![Screenshot 2025-04-24 033510](https://github.com/user-attachments/assets/eea21147-06c1-4b22-904f-8944853f3e83)

 
- Sales by Outlet Location (Bar Chart)
  - Metro and urban outlets outperform semi-urban/rural locations.
  - Opportunities exist to boost performance in under-performing regions.
 ![Screenshot 2025-04-24 033519](https://github.com/user-attachments/assets/30c401a6-4556-4995-8180-6a7c896b936f)


- Link to view - <a href="https://github.com/Simran1028/Blinkit-Analysis/blob/main/Blinkit_Analysis.ipynb">Jupyter Notebook-Blinkit Analysis</a>

## Conclusion
- Regular fat and mid-range priced products perform best across Blinkit’s inventory.
- Older and medium-sized outlets generate stronger sales, likely due to experience and balance of accessibility.
- Urban expansion, improved product placement, and inventory alignment with consumer behavior can significantly improve performance.
