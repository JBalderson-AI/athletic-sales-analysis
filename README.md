# athletic-sales-analysis
Module 5: Preparing data with pandas

## Project Overview
This project involves analyzing sales data from two annual sales datasets using pandas in Python. The analysis includes data loading, cleaning, transformation, and aggregation to derive business insights about product sales across different dimensions including retailers, regions, and time periods.

## Features
The analysis script provides the following capabilities:

1. **Data Loading and Integration**
   - Reading multiple CSV files
   - Combining data from different sources
   - Resetting and properly formatting indices

2. **Data Cleaning and Transformation**
   - Checking and handling null values
   - Converting data types (particularly dates to datetime format)
   - Standardizing column names

3. **Sales Analysis by Location**
   - Aggregating sales by region, state, and city
   - Identifying top-performing geographical areas
   - Using both groupby and pivot table approaches

4. **Retailer Performance Analysis**
   - Determining which retailers have the highest sales
   - Analyzing total units sold by retailer
   - Focusing on specific product categories like Women's Athletic Footwear

5. **Time-Based Analysis**
   - Daily sales aggregation and trend analysis
   - Weekly sales resampling and performance tracking
   - Identification of peak sales periods

## How to Use
The provided Jupyter Notebook contains all the code necessary to perform these analyses. To use this code:

1. Ensure you have pandas and related libraries installed:
   ```
   pip install pandas numpy matplotlib seaborn ipython
   ```

2. Set up your directory structure with the CSV files in the same location as the notebook or adjust file paths accordingly.

3. Execute the notebook cells in sequence to:
   - Load and prepare the data
   - Perform the analyses
   - Generate visualizations and summary tables

4. Modify specific filters (e.g., product category, date ranges) to focus on different aspects of the data.

## Key Insights That Can Be Derived
This code can help answer business questions such as:

- Which geographical areas drive the most sales?
- Which retailers are the most effective at selling specific product categories?
- What are the sales trends over time, and when do peak sales occur?
- How do different product categories perform across retailers and regions?

## Extensions and Future Work
This analysis framework can be extended to:

- Add more sophisticated visualizations
- Implement predictive models for sales forecasting
- Add customer demographic analysis if data is available
- Incorporate profit margin analysis alongside pure sales metrics

## Requirements
- Python 3.x
- pandas

## Notes
- This code assumes certain column names in your CSV files. Adjust column references as needed to match your actual data structure.
- The formatting code at the end of the notebook will significantly improve the visual presentation of your results.

## Contact
Jill Balderson - JBalderson-AI
