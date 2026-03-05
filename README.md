# Market Basket Analysis using Apriori & FP-Growth

## Project Overview
This project analyzes retail transaction data to identify frequently purchased product combinations using association rule mining techniques. The objective is to uncover patterns that can support cross-selling strategies, product placement optimization, and bundle promotions in retail environments.

## Dataset
- 9,835 retail transactions
- 2,123 unique customers
- 167 unique products

Each transaction contains the set of items purchased together during a single shopping visit.

## Tools & Technologies
- Python
- Pandas
- MLxtend
- Apriori Algorithm
- FP-Growth Algorithm
- Jupyter Notebook

## Project Workflow
1. Data Cleaning and Transformation
2. Converting transaction data into basket format
3. Frequent Itemset Mining using Apriori
4. Association Rule Generation
5. Rule Evaluation using Support, Confidence, and Lift
6. Interpretation of product relationships

## Key Findings
- Generated **97 frequent itemsets** with minimum support of 0.01.
- Identified strong product associations with **confidence values above 65%**.
- Certain product combinations showed **lift values greater than 1.8**, indicating strong co-purchase behavior.
- Items such as dairy products, bakery items, and beverages frequently appeared together in transactions.

## Business Impact
Retailers can use these insights to:
- Design bundle promotions
- Improve product placement
- Increase cross-selling opportunities
- Improve average transaction value

## Author
Deekshitha Duddola
