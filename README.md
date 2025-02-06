# Handling-Missing-Values-Complete-Case-Analysis-

**Missing Values**
A. Remove Them
B. Impute

# A. Remove Them : 
**Complete Case Analysis** also called *List wise deletion*
CCA means literaly analyzing only those observations for which there is information in all of the variables in the dataset.

# Advantages : 
1. Easy to implement as no data manipulation  required.
2. preserves variable distribution ( if data is MCAR, then the distribution of the reduced dataset should match the distribution in the original dataset ).

# Disadvantages : 
1. It can include a large function of the original dataset ( if missing data is abundant ).
2. Exclude observation could be informative for the analysis ( if data not missing at random ).
3. When using our models in production, the model will not know how to handle missing data.
