# Online Retail Data Analysis Report

## 1. Introduction

I analyzed an online retail dataset using Python. My goal was to understand the data, find missing values, and identify sales patterns.

## 2. Dataset Details

* Total rows: 541,909
* Total columns: 8
* Tools used: Python, Pandas, and VS Code

## 3. What I Found

* 135,080 rows have missing CustomerID values.
* 5,268 duplicate rows were found.
* 10,624 rows have negative quantities.
* 2 rows have negative prices.
* 2,515 rows have zero prices.
* The United Kingdom has the highest positive sales value in my analysis: 9,025,222.08.

## 4. What These Results Mean

Missing customer IDs make it harder to study individual customers. Duplicate rows need checking. Negative quantities may represent returned goods. Negative and zero prices need further investigation.

## 5. Conclusion

This analysis helped me understand the dataset and find data-quality problems. I will use these findings to create charts and study sales trends.

## 6. Data Visualization

I created two charts using Python, Pandas, and Matplotlib.

### Chart 1: Top 10 Countries by Sales

This bar chart compares sales values across the ten countries with the highest sales in the filtered dataset. The United Kingdom has the highest sales value.

### Chart 2: Monthly Sales Trend

This line chart shows how sales values change from month to month. It helps identify changes and patterns in sales over time.

### Conclusion

The charts make it easier to understand sales patterns and compare countries. The generated charts are saved as PNG image files.
