Modeling text topics with Latent Dirichlet Allocation
In many cases, it is good to think of data as belonging to more than one cluster or category. For example, if we have a model for text data that includes both "Politics" and "World News" categories, then an article about a recent meeting of the United Nations should have membership in both categories rather than being forced into just one.

With this in mind, we will use GraphLab Create tools to fit an LDA model to a corpus of Wikipedia articles and examine the results to analyze the impact of a mixed membership approach.

In this assignment you will

apply standard preprocessing techniques on Wikipedia text data
use GraphLab Create to fit a Latent Dirichlet allocation (LDA) model
explore and interpret the results, including topic keywords and topic assignments for a document

Modeling text data with a hierarchy of clusters
Hierarchical clustering refers to a class of clustering methods that seek to build a hierarchy of clusters, in which some clusters contain others. In this assignment, we will explore a top-down approach, recursively bipartitioning the data using k-means.