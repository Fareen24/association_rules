# Supermarket Transaction Analysis Using Apriori Algorithm

## Overview

This project involves analyzing supermarket transaction data to uncover valuable insights using the Apriori algorithm. The analysis aims to identify frequent itemsets and derive association rules that can inform business decisions for supermarket owners.

## Assignment Objectives

1. **Run the Apriori Algorithm on a Provided Toy Dataset**: 
   - Implement the Apriori algorithm on a given toy dataset to identify frequently bought itemsets.
   - Interpret the results to understand customer purchasing behavior.

2. **Explore the Checkpoint Dataset Using Pandas and Plotly**: 
   - Load and preprocess the checkpoint dataset using Pandas.
   - Visualize the dataset using Plotly to uncover patterns and trends.

3. **Run the Apriori Algorithm on the Checkpoint Dataset**: 
   - Apply the Apriori algorithm to the checkpoint dataset.
   - Interpret the findings and generate association rules.

4. **Business Plan Suggestion**: 
   - Based on the analysis, propose a clear business plan to the supermarket owners that leverages the insights gained.

## Methodology

### 1. Running the Apriori Algorithm on Toy Dataset

- The toy dataset consists of various transactions where each row represents a customer basket.
- The Apriori algorithm was applied with a minimum support threshold to identify frequently bought items.

### 2. Data Exploration with Pandas and Plotly

- The checkpoint dataset was explored using Pandas for data manipulation and cleaning.
- Visualizations were created with Plotly to highlight key trends, such as item frequencies and purchasing patterns.

### 3. Running the Apriori Algorithm on Checkpoint Dataset

- After preprocessing, the Apriori algorithm was executed on the checkpoint dataset to discover frequent itemsets.
- Association rules were generated based on the identified itemsets, focusing on metrics such as confidence and lift.

## Results

### Toy Dataset

- **Frequent Itemsets**: Identified combinations of items that customers frequently purchased together.
- **Association Rules**: Generated rules indicating the likelihood of customers purchasing certain items based on their existing purchases.

### Checkpoint Dataset

- **Visual Insights**: Key visualizations revealed trends in customer purchases, such as popular items and seasonal variations.
- **Frequent Itemsets**: Similar to the toy dataset, frequent itemsets were identified, providing insights into customer behavior.

## Business Plan Suggestions

Based on the findings from both datasets, the following business strategies are recommended for supermarket owners:

1. **Cross-Selling Opportunities**: 
   - Utilize the association rules to create product bundles and promotions for frequently bought items. This can enhance sales and improve customer satisfaction.

2. **Store Layout Optimization**: 
   - Rearrange the store layout to place frequently purchased items near each other, making it easier for customers to find related products.

3. **Targeted Promotions**: 
   - Implement targeted marketing campaigns based on the identified customer purchasing patterns. For example, offer discounts on items commonly bought together.

4. **Inventory Management**: 
   - Adjust inventory levels based on insights gained from the frequent itemsets to ensure that popular products are always in stock, reducing missed sales opportunities.


## Requirements

- Python (version 3.x)
- Pandas
- mlxtend
- Plotly
- Matplotlib (optional for additional visualizations)

# Disclaimer 
This is for education purposes only
