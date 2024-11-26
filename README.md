# Retail Data Analytics - Dataset Analysis

This repository contains an analysis of the **Retail Data Analytics** dataset sourced from Kaggle. The dataset includes sales information for various products across different stores and regions. The analysis applies Python-based techniques for data cleaning, transformation, and visualization.

## Dataset Overview
The dataset contains the following columns:

1. **Order ID**: Unique identifier for each order.
2. **Order Date**: Date when the order was placed.
3. **Ship Date**: Date when the order was shipped.
4. **Ship Mode**: Mode of shipment (e.g., First Class, Second Class).
5. **Customer ID**: Unique identifier for each customer.
6. **Customer Name**: Name of the customer.
7. **Segment**: The market segment to which the customer belongs (e.g., Consumer, Corporate).
8. **Country**: The country where the order was placed.
9. **City**: The city where the order was placed.
10. **State**: The state where the order was placed.
11. **Postal Code**: The postal code of the shipping address.
12. **Region**: The region where the order was placed.
13. **Product ID**: Unique identifier for each product.
14. **Category**: The category of the product (e.g., Office Supplies, Furniture).
15. **Sub-Category**: The sub-category of the product (e.g., Binders, Chairs).
16. **Product Name**: The name of the product.
17. **Sales**: The sales amount for the order.
18. **Quantity**: The quantity of products ordered.
19. **Discount**: The discount applied to the order.
20. **Profit**: The profit generated from the order.

## Application-Based Python Questions

The following questions were addressed using Python to analyze the dataset:

1. **Data Cleaning**: Correct inconsistencies in 'Order Date' and 'Ship Date'.
2. **Data Transformation**: Calculate shipping duration and analyze regional distributions.
3. **Time Series Analysis**: Analyze monthly sales trends over the years.
4. **Data Aggregation**: Aggregate sales by product category and sub-category.
5. **Correlation Analysis**: Investigate the correlation between discount percentage and profit.
6. **Outlier Detection**: Identify outliers in 'Sales' and 'Profit'.
7. **Data Filtering**: Filter orders with discounts over 20%.
8. **Pivot Table Analysis**: Pivot sales and profit by region and segment.
9. **Text Data Analysis**: Analyze product names associated with high sales.
10. **Customer Segmentation**: Segment customers based on total purchase amount.
11. **Advanced Visualization**: Visualize product category sales using heatmaps.
12. **Data Resampling**: Resample data for weekly sales trends.
13. **Rolling Window Calculation**: Calculate and visualize rolling averages of sales.
14. **Data Merging**: Merge additional marketing spend data and analyze its impact.
15. **Custom Aggregation**: Calculate the weighted average discount by category.
16. **Data Binning**: Bin 'Sales' into quartiles and analyze profit distribution.
17. **Data Sorting and Ranking**: Rank products based on sales and profit.
18. **Complex Data Extraction**: Extract delayed orders and assess their impact on satisfaction.
19. **Data Deduplication**: Remove duplicate entries based on 'Order ID' and 'Product ID'.
20. **Seasonal Sales Analysis**: Analyze seasonal sales patterns by category.

## Python Tech Stack

The following Python libraries and tools were used for the analysis:

- **Pandas**: For data cleaning, manipulation, and analysis.
- **NumPy**: For numerical calculations and handling missing data.
- **Matplotlib**: For visualizing data trends and distributions.
- **Seaborn**: For creating advanced visualizations, such as heatmaps and pair plots.
- **Scikit-learn**: For correlation analysis and outlier detection.
- **Jupyter Notebook**: For executing Python code in an interactive environment.
- **Datetime**: For handling date-time operations and transformations.

## Conclusion

This analysis provides valuable insights into retail sales trends, product performance, and customer behavior. The Python-based techniques applied in data cleaning, transformation, and visualization allow for a deeper understanding of the dataset, leading to actionable insights for business optimization.

Feel free to explore the code and visualizations in the repository to dive deeper into the analysis.
