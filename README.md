# Market-Basket-Analysis
Market Basket Analysis also known as the Association Rule, it's a mathematical technique. According to Market Basket Analysis if you buy a certain group of items you are most likely to buy another set of items. Market Basket is mostly used to analyze customer behavior and helps to increase sales.
According to the Apriori algorithm, all sub-clusters of an uncommon itemset can't be frequent, or in other words, if an itemset doesn't meet the minimal threshold value, it can't be frequent.



The market basket analysis is used by retailers to determine the purchasing patterns of customers. It often reveals product groupings and products that are likely to be purchased together. We have used the association rule for this. It counts the frequency of items that occur together, seeking to find associations that occur far more often than expected.
The association rule was determined by using the frequent itemsets with a minimum threshold of 

1. We used a lift and confidence for the rules of associations.
2. The confidence of an association rule is a percentage value that shows how frequently the rule head occurs among all the groups containing the rule body. The confidence value indicates how reliable this rule is. The higher the value, the more likely the head items occur in a group if it is known that all body items are contained in that group.
 The lift value of an association rule is the ratio of the confidence of the rule and the expected confidence of the rule. The expected confidence of a rule is defined as the product of the support values of the rule body and the rule head divided by the support of the rule body.
 
 
 
Here we have done baskets for the Top 3 countries having Online Retail Market.



From the above Heatmaps we can see that
In the UK for the value 7.7 we can see that the consequence is frozenset(jumbo bag polkadot) and the antecedent for it is frozenset(jumbo bag red retrospot). So, if a person in UK buys a
Polkadot jumbo bag is most likely to buy a red retrospot jumbo bag as well. And the same goes for all of them.
