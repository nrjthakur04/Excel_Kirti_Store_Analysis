# Annual Sales Analysis for Kriti Store (2024)

## Table of Contents

- [Project Overview](#project-overview)
- [Steps Taken](#steps-taken)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview

This data analysis project aims to provide insights into the sales performance of the Kirti store over the year. By analyzing various aspects of the sales data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the store's performance. So that, Kirti store can understand their customers and grow more sales in 2025.

### Steps Taken

In this project, I've created an annual sales report for Kriti Store for the year 2024. The process involved data cleaning, processing, and analysis using Excel. Below are the detailed steps taken during the project.

1. Data Cleaning

Filter Option: To enable the filter option in all columns, use the shortcut Alt + Shift + L.

Consistency Check: Verified that all columns contain consistent values, ensuring numeric columns are entirely numeric and gender values are consistent.

Data Replacement: Used Ctrl + F to find instances of "M" and replaced them with "Male".

Completion: Confirmed that the data cleaning phase is complete.

2. Data Processing

Data Calculation: To facilitate analysis, created relationships between age and gender by forming age groups.

Age Group Column: Added a new column titled "Age Group" next to the "Age" column with the formula:
=IF(T2>=50,"Senior",IF(T2>=30,"Adult","Teenager")).

Performance Optimization: To prevent system slowdowns due to these changes, selected the column, copied it using Ctrl + C, and then pasted as values using Ctrl + Shift + V.

3. Data Analysis

Sales Analysis: Addressed a query regarding the highest sales by creating a "Month" column next to the "Date" column. Used the formula:
=TEXT(G2,"mmm") to extract the month from the date.

Highlighting New Calculations: Filled colors in newly created cells to highlight them as they were derived from calculations.

Amount Conversion: Converted amount values from lakhs to millions in the pivot table. Clicked on the Amount area, selected "Format Axis," and modified the format code to (0,,'M') or (0.00'M').

Gridlines Management: To remove background gridlines, navigated to View, then under Show, deselected Gridlines.

Pivot Table Refresh: To update the pivot table after data changes, selected the chart and clicked on Refresh under PivotTable Analyze.

Grand Total Removal: To remove grand totals, went to the Design tab and selected "Off" for rows and columns.

4. Visualization

Sales Comparison: To compare sales between men and women, selected the numbers or percentage values. Used Format Data Labels to display the percentage under Label Options.

Pie Chart Rotation: To adjust the pie chart's orientation, clicked on the pie chart and changed the angle of the first slice under Format Data Series.

Top States Filtering: To filter out the top 5-10 states based on sales amounts, right-clicked on the row labels, chose Filter, and selected Top 10 to pick the desired number of top rows.

Age Group Analysis: To determine the percentage of orders by age group, right-clicked on the data and selected Show Values As to click % of Grand Total.

5. Adding Slicers

Slicer Integration: Slicers can only be added if it’s a pivot chart. Navigated to PivotChart Analyze, clicked on Insert Slicer, and selected the desired options.

Report Connections: Right-clicked on the slicer, went to Report Connections, and made selections based on preferences to connect it with other sheets.


### Data Sources

Sales Data: The primary dataset used for this analysis is the "Kirti Store Dataset.xlsx" file, containing detailed information about each sale made by the store and is attached in this repo.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

- Compare the sales and orders using single chart.
- Which month got the highest sales and orders?
- Who purchased more- men or women in 2024?
- What are the different order status in 2024?
- List top 5 states contributing to the sales.
- Relation between age and gender based on number of orders.
- Which channel is contributing to the maximum sales?
- Which is the highest selling category?

### Results/Findings

![visualisation](https://github.com/user-attachments/assets/bf583a93-4dbf-4b42-a9f7-08f0f7712099)


The analysis results are summarized as follows:
1. Women are more likely to buy as compared to men (65%)
2. Maharashtra, Karnataka and Uttar Pradesh.
3. Women
4. .....
5. Maharashtra, Karnataka and Uttar Pradesh
6. Adult age group (30-49 yrs) is maximum contributing (50%)
7. Amazon, Flipkart and Myntra are max contributing (80%)
8. .......


### Recommendations

Based on the analysis, we recommend the following actions:
- Target Audience: Focus on women aged 30-49 years in Maharashtra, Karnataka, and Uttar Pradesh.
- Platforms: Utilize Amazon, Flipkart, and Myntra to showcase ads, offers, and coupons.
- Localization: Customize campaigns with regional targeting for higher engagement.
