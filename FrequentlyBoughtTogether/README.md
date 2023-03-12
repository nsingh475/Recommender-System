# Frequently Bought Together Recommendation System

Frequently Bought Together method relies only on the history of items purchased together in the same order at the store. It does require that the store have a sufficiently long history of transactions to make associations. This recommendation system is that it does not require us to know anything about the user other than which item they are viewing.


### Terms
1. Item: The product or thing that we are trying to recommend based on its association with other items. In a grocery store, these might be products such as Milk, Diapers, and Beer.
2. Itemset: One or more items that have been purchased together.
3. Association Rules: The rules that we will calculate from the itemsets to determine the recommendations. Once we have the Association Rules, we can use them to recommend items that are frequently purchased together with the item the customer is viewing.


### Metrics
1. Support: The probability of finding an itemset in any given order.
                  Support = Number of orders containing all items in itemset / Total number of orders
2. Confidence: The probability of finding Item 2 in an order given that Item 1 is in the order. This tells us how likely an item is to be purchased along with another specific item.
                  Confidence = Number of orders containing item 1 and item 2 / Total number of orders containing item 1
3. Lift: Lift value of 1 means the two items are independent, a value greater than one means the items are more likely to occur together than if they were independent, and a value less than one indicates that the items are less likely to occur together than if they were independent.
                     Lift = Support({Item 1, Item 2}) / (Support({Item 1)* Support({Item 2}))


### Algorithms for Frequently bought product
1. Apriori: It is the most famous algorithm for data mining association rules because of its simplicity. It can take a long time to compute on a large dataset because it has a time complexity of O(n²).
2. FP Growth: It is a much faster algorithm that uses a tree-based approach that limits data reads to two passes. This results in linear time complexity O(n), saving significant computational resources as the dataset grows. 


### Project Implementation and workflow
1. Importing Libararies
2. Importing Dataset
3. Data Cleaning
4. Restructuring data
5. Model Build - Apriori and FP Growth Algorithm
6. Showing that both the algorithms generate the same itemset
7. Calculating assosciation rule
8. Making predictions


