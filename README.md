# Data Science/ Machine Learning ToolBox

Notebook with examples of common scenarios while doing DS/ML

## Correlations
- Has many types of variable association methods. 
- Some are functions from Pandas such as .corr for Pearson and Spearman, other are UDF such as Cramers'V, Theil's U , Correlation Ratio and Time Lagged Cross Correlation. 
- The intention is to display different scenario where different data types can be associated.

## Correlation Clustering
- Applies an unsupervised hierarchical clustering using correlation matrix
- The correlation matrix is converted to a distance matrix 
- Each cluster holds correlated variable, and between each clusters, variables should be less similar
- Based on this logic, the pipeline searches for multicollinearity and return a list of variables to remove. 
