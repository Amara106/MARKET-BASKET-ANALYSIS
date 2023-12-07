# MARKET-BASKET-ANALYSIS
This repository contains a Python script for performing Market Basket Analysis using the Apriori algorithm. The analysis is applied to a grocery sales dataset to discover associations between different products.

Code Structure
Data Loading and Cleaning:
Load the grocery sales data and perform initial data cleaning.
Convert 'Member_number' to a string and 'Date' to datetime format.
plotting bar charts and line grsph to show the least sold items, the most sold items and the sales by month.

Unique Transactions:
Create a 'Transaction' column to group items purchased per customer per day.

Cross-Tabulation (Basket Creation):
Create a cross-tabulation to represent the frequency of items in each unique transaction.
Create a binary-encoded DataFrame.

Apriori Algorithm and Association Rules:
Apply the Apriori algorithm to generate frequent itemsets.
Use association rules, focusing on Zhang's metric for evaluation.

Heatmap Visualization:
Visualize product associations using a heatmap.
Interpret the heatmap to understand frequent itemsets.
Positive Association Visualization:

Explore pairs with positive Zhang's metric to highlight positive associations.
