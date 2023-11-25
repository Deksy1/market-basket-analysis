Market Basket Analysis Project

Introduction:

Market Basket Analysis is a data mining technique that provides insights into customer purchasing behavior by identifying associations between products frequently purchased together. This project explores the application of Market Basket Analysis to a retail dataset using the Apriori algorithm and association rules.

Dataset:

The dataset used in this project is sourced from Git Hub. It contains transactional data with information on customer purchases, dates, and specific items bought.

Methodology:

Data Preprocessing:

The dataset is loaded into a pandas DataFrame.
Date columns are converted to datetime format, and a new 'uniqueTransaction' column is created to group items purchased per customer per day.
Binary Encoding:

A binary-encoded DataFrame ('apriori_df') is generated, representing the presence or absence of items in each transaction.
Apriori Algorithm:

The Apriori algorithm is applied to identify frequent itemsets based on a specified minimum support threshold.
Association Rules:

Association rules are generated using the frequent itemsets, and the 'lift' metric is used for evaluation.
Visualization:

The project includes a heatmap visualization of product associations, showcasing the strength of relationships between items based on the 'lift' metric.
Dependencies:

pandas
mlxtend
seaborn
matplotlib
Usage:

Clone the repository.
Install the required dependencies.
Execute the Jupyter Notebook or Python script.
Results:

The project provides actionable insights into product associations, aiding in strategic decision-making for product placement, promotions, and inventory management.

Feel free to explore, contribute, and adapt this project for your specific use case!
 main
