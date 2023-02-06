# Market-Basket

A market basket analysis would help understand the purchase behavior of customers. In a shopping cart, normally, there are several items as a combination depending on the preference of different customers. Knowing what items would come after particular items, shelf planners would have better ideas of what items should be put together. Also, retail managers would better understand what sorts of items should be stored in the warehouse to prevent insufficiency.

1.2 Analytics Tool and Dataset
This analysis uses Python as an analytics tool.

There 2 given datasets. One contains 38765 transaction records with member IDs, transaction dates, and item names. The other one contains 14963 rows with only the items per transaction.

2. Prepare
2.1 Analysis Plan
The analysis plan is to answer the questions.

What are the most frequently sold items?
what are the consequents of the chosen items?
How confident do the consequents come after the items?
What are the most important items that should always be in the store?
How the item network looks like?
What is the difference between analyzing the data based on customer ID and different transactions?
2.2 Method
This analysis will load the 2 datasets. The first one with member IDs will be used for creating a basket model based on IDs. The other one will be used for creating a model based on transactions. Literately, the total number of sold items should be the same. The analysis steps are as below.

Prepare the 2 .csv files
A bar chart to see the most frequently sold items
A quick look at the relationship between items
Select an item to proceed a further analysis
A heatmap to review the association between antecedents and consequents
A network graphic to know the connections of the selected item

3. Process
First of all, load the essential packages and read the 2 datasets.
