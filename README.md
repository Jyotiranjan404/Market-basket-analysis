# Market-basket-analysis
![market-basket-analysis-retail](https://user-images.githubusercontent.com/84494071/132131101-c9399ab2-9681-4d7f-9e7c-8e754c8381ff.jpg)

# Introduction
Market Basket Analysis is one of the key techniques used by large retailers to uncover associations between items.It helps to identify most frequently saling items.

# Why market basket analysis ?
In Order to do cross sale,up sale and Recommend some products to customers.Aim here is, if some "X" customer is plaining to buy something, i am ready with another item to recomend them,In that way sales also increases.

# What association rule generate ?
1. Lift
2. Support
3. Confidence

![AR_1](https://user-images.githubusercontent.com/84494071/132131547-86f0ec6e-66f5-4f47-9109-2abd4b93e35e.png)

# Steps we do in association rule:
- Creating Frequencies by using apriori algorithm.
- Passing those Frequencies to association rules to generate lift, support and Confidence.
- Which items are having very good lift,support and confidence, we can take those combinations in order to do some cross selling.

# Libraries we need:

- from mlxtend.frequent_patterns import apriori
- from mlxtend.frequent_patterns import association_rules

# Implementation with real time data











