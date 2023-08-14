# Design tree : is a flow chart, that help you make decisions based on previous experiences.
Model parameters such as the depth of the decision tree can also be set, to lower the risk of overfitting or an overly complex tree. 


- The main benefits of using a decision tree in machine learning is its simplicity and decision- making process is easy to visualize and understand 

- it is built by recursive partitioning algorithm 

Example of a decision tree : 
1- Classification trees (yes/no)
2- Regression trees(continuous data)


- CART Algorithm (Classification and Regression tree):

1- Gini impurity (default)
- measures the frequency at which any element of the dataset will be mislabeled whin it is randomly labeled.
- the measure of impurity or the purity that is used in building a decision tree. 
- much faster (less computation) 

2- Entropy 

- measure of Information that indicates the disorder of the feature with the target.
- The uncertainty in our dataset or measure of disorder.
- The result is slightly better. 


-- Entropy and information Gain 
Entropy between 0,1 
If entropy = 1 then this feature is not enough to determine the output(week feature) and it will not be used in the model 

If entropy = 0 this feature is strong so we will use it to split the data .
Information gain will determine the best feature to split the data with it .
We select the feature with high information gain 
We will calculate everything for each level of the tree. 
