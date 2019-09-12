# CSE601


## Mining Association Rules

- Two-step Approach:

   1. Frequent Itemset Generation 
      - Generate all itemsets whose support ≥ minsup
   2. Rule Generation
      - Generate high confidence rules from each frequent itemset, where each rule is a binary partitioning of a frequent itemset
