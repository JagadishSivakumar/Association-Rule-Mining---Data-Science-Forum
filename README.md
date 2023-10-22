# Association-Rule-Mining_Data-Science-Forum
Associate Rule Mining on groceries dataset for Data Science Forum 2023

### Apriori Params:
- Transactions: List of lists that contain the items in each transaction.

- min_support: Minimum support of relations; means that the relation should be present in at least 3 transactions out of total transactions.

- min_confidence: Minimum confidence of relations; means that the relation should be found true in at least 20% of the total transactions in which the antecedent is present.

- min_lift: Minimum lift of relations; means that the relation should be at least 3 times more than the confidence.

- min_length: Minimum number of items in the relation.

- max_length: Maximum number of items in the relation.


### Key Metrics
* Confidence: Conditional probability of item B given A (i.e; number of times if 'x' is bought then 'y' is also bought together)

* Support: Probability of an item A being bought (i.e; the number of times 'x' is bought divided by the total number of transactions)

* Lift: Ratio of confidence to support (i.e; confidence/support). This is used to find the strength of the rule.
