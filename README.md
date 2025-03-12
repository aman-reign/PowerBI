# PowerBI
# Blinkit-Dashboard

## Repository Structure
- Data: [Blinkit Grocery Data (.xlsx)](https://github.com/aman-reign/PowerBI/blob/main/BlinkIT%20Grocery%20Data.xlsx) – Contains raw sales data used for analysis.
- Dashboard: [Blinkit Sales Dashboard (.pbix)](https://github.com/aman-reign/PowerBI/blob/main/blinkitdashboard.pbix) – Power BI file containing all transformations and visualizations. 
- Image: [Dashboard Screenshot](https://github.com/aman-reign/PowerBI/blob/main/blinkit-dashboard.png) – Preview of the Blinkit Sales Dashboard

## Problem Statement

This Blinkit Sales Dashboard provides a data-driven analysis of sales performance across different supermarket outlets. It showcases key metrics such as total sales, average sales, number of items sold, and average rating.

Retail businesses often struggle with understanding sales distribution, outlet performance, and product demand. This dashboard aims to address these challenges by:
- Identifying which outlets and locations contribute the most to sales.
- Analyzing average sales across different item categories.
- Comparing the performance of different supermarket types to optimize decision-making.
- Helping businesses track historical sales trends to forecast future performance.

## Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a xlxx file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Cleaned and preprocessed the data using Python (pandas) or Power BI data transformation tools to handle missing values and inconsistencies.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : Visual filters (Slicers) were added for four fields named "Outlet Size", "Outlet location" & "Item Type 
- Step 7 : Four card visuals were added to the canvas, one representing relevant KPIs such as Total Sales, Average Sales, Number of Items Sold, and Average Rating.
- Step 8: Designed Outlet Establishment Graph to show sales trends over time. Also designed Donut Charts & Bar Graphs for item type sales distribution and outlet performance.


