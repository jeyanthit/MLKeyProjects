## Modeling text topics with Latent Dirichlet Allocation

In many cases, it is good to think of data as belonging to more than one cluster or category. For example, if we have a model for text data that includes both "Politics" and "World News" categories, then an article about a recent meeting of the United Nations should have membership in both categories rather than being forced into just one.

With this in mind, we will use GraphLab Create tools to fit an LDA model to a corpus of Wikipedia articles and examine the results to analyze the impact of a mixed membership approach.

In this project,

    •	  apply standard preprocessing techniques on Wikipedia text data
    •	  use GraphLab Create to fit a Latent Dirichlet allocation (LDA) model
    •	  explore and interpret the results, including topic keywords and topic assignments for a document


## Modeling text data with a hierarchy of clusters
Hierarchical clustering refers to a class of clustering methods that seek to build a hierarchy of clusters, in which some clusters contain others. In this assignment, we will explore a top-down approach, recursively bipartitioning the data using k-means.

##  Latent Dirichlet Allocation for Text Data

    •	apply standard preprocessing techniques on Wikipedia text data
    •	use GraphLab Create to fit a Latent Dirichlet allocation (LDA) model
    •	explore and interpret the results, including topic keywords and topic assignments for documents
    •	Recall that a major feature distinguishing the LDA model from our previously explored methods is the notion of mixed membership.


Throughout the course so far, our models have assumed that each data point belongs to a single cluster. k-means determines membership simply by shortest distance to the cluster center, and Gaussian mixture models suppose that each data point is drawn from one of their component mixture distributions. In many cases, though, it is more realistic to think of data as genuinely belonging to more than one cluster or category - for example, if we have a model for text data that includes both "Politics" and "World News" categories, then an article about a recent meeting of the United Nations should have membership in both categories rather than being forced into just one.

With this in mind, we will use GraphLab Create tools to fit an LDA model to a corpus of Wikipedia articles and examine the results to analyze the impact of a mixed membership approach. In particular, we want to identify the topics discovered by the model in terms of their most important words, and we want to use the model to predict the topic membership distribution for a given document.
