Market Basket Optimization – Product Association

Overview

This project focuses on Market Basket Optimization, using association rule mining to find relationships between products. The goal is to identify frequently bought-together items, which can help businesses optimize their sales strategies and recommendations.

Features

Data Preprocessing:

Cleaning and structuring transactional data.

Formatting data for association rule mining.

Association Rule Mining:

Implementing Apriori and FP-Growth algorithms.

Extracting frequent itemsets and association rules.

Insights & Visualization:

Identifying top product combinations.

Visualizing association rules using network graphs.

Dataset

Contains transactions with multiple products per purchase.

Used to discover frequent product associations.

Installation

Install required dependencies:

pip install pandas numpy mlxtend matplotlib seaborn

Usage

Run the script to extract frequent itemsets and generate association rules:

python market_basket_optimisation.py

Results

Discovered key product associations.

Identified strong rules for sales optimization.

Future Improvements

Implement a recommendation system based on frequent itemsets.

Test additional algorithms like Eclat for association rule mining.

License

This project is open-source and available under the MIT License.

