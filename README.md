# Discount Data Analysis for Eniac: A Comprehensive Overview

## Overview

This project presents a thorough analysis of Eniac's discounting strategy and its impact on revenue. The analysis is conducted by a team of data analysts, including Hanne Prüfer, Helene Rebelo, Irene da Cruz, and Roberto Cavotti. The primary focus is on understanding how monthly revenue and the average discount rate influence sales performance in the years 2017 to 2018. Additionally, the study delves into the relationship between discounts, seasonal shifts, special events, product categories, and various pricing and quantity dynamics.

## Objective

To assess the impact of Eniac's discounting strategy on sales performance, categorization, and seasonal variations. The analysis aims to provide insights into optimizing discount distribution across product categories and months.

## Data Source

The data for this analysis is sourced from Eniac's discount database, covering the period from 2017 to 2018. The dataset was cleaned to address issues such as a corrupted database, incongruent data, double dots numbers, and general data quality concerns.

## Tools Used

- Python with Pandas for data manipulation and cleaning
- Seaborn for statistical visualization
- Excel for additional data manipulation and cleaning

## Folder Structure

- `/src`: Contains Python scripts and SQL code for data cleaning and analysis.
- `/docs`: Project documentation, reports, and presentations.

## Analysis Summary

The analysis reveals key insights into the impact of discounts on Eniac's sales performance:

1. **Monthly Revenue and Average Discount Rate**: There is a positive correlation between monthly revenue and the average discount rate. Specifically, periods with higher average discounts show an increment in sales performance.

2. **Seasonal Shifts and Special Events**: Discounts significantly influence sales during seasonal shifts and special events. Applying discounts during these periods increases the likelihood of generating sales.

3. **Discounts Across Product Categories**: Discounts vary based on the pricing and quantity of different product categories. Lower-priced items tend to have higher discounts, and products with higher quantities sold also attract higher discounts.

4. **Effect on Revenue per Day by Category**: Discounts impact the revenue per day, with variations observed across different product categories, especially those with the highest discounts and most sold products.

## Data Cleaning

The dataset underwent a rigorous cleaning process to ensure data integrity:

1. **Corrupted Database**: Identified and addressed issues that affected the overall integrity of the database.
2. **Incongruent Data**: Resolved inconsistencies, mismatched, and/or duplicate data.
3. **Double Dots Numbers**: Rectified anomalies in numerical values, focusing on duplicated or irregular decimal points.
4. **Data Quality Concerns**: Mitigated issues affecting the reliability and completeness of the dataset.

## Data Improvement Recommendations

To enhance the dataset, the following recommendations are proposed:

1. **Standardize Currency Values**: Implement a standardized approach for writing values in currency.
2. **Avoid Missing Data**: Ensure completeness by addressing blank columns and rows.
3. **Include Customer Data**: Integrate customer data to assess the impact of discounts on individual customer behaviors.
4. **Additional Columns for Cost Calculation**: Include new columns for product costs, delivery values, and taxes to calculate profit margins.

This analysis sets the foundation for optimizing Eniac's discounting strategy, with a focus on increasing revenue and aligning discounts with specific product categories and seasonal trends.

## Authors

- [Hanne Prüfer](https://github.com/HannePruefer)
- [Helene Rebelo](https://github.com/HeleneRebelo)
- [Irene da Cruz](https://github.com/IreneDaCruz)
- [Roberto Cavotti](https://github.com/RobertoCavotti)
