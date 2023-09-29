# ML-Price-Optimization
ProjectPro-inspired: Retail price optimization using regression trees. Analyzing restaurant sales data, applying OLS and price elasticity to set ideal prices, enhancing profitability.

#Data

Dynamic Pricing Dataset
The data is contained in three CSV files.

> Cafe - Sell MetaData.csv This file has details about sales made by the cafe. 

>> Columns: Sell ID, Sell Category, Item ID, Item Name

> Cafe - Transaction - Store.csv This file contains information about transactions and sale receipts of the cafe.

>> Columns: Calendar Date, Price, Quantity, Sell ID, Sell Category

> Cafe - DateInfo.csv This has date information corresponding to the transactions performed.

>> Columns: Date, Year, Holiday, Weekend, School Break, Temperature, Outdoor

The code initiates an exploratory analysis for each CSV file, collating them for subsequent in-depth examination. Upon consolidation, a granular assessment ensues, focusing on each menu item's pricing dynamics. Regression trees and Ordinary Least Squares (OLS) regression come into play to meticulously gauge the price elasticity of each product. This multifaceted analysis equips us with valuable insights into how price changes impact demand, facilitating strategic decision-making to optimize menu pricing effectively.
