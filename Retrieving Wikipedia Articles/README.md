Nearest Neighbors
When exploring a large set of documents -- such as Wikipedia, news articles, StackOverflow, etc. -- it can be useful to get a list of related material. To find relevant documents you typically

Decide on a notion of similarity
Find the documents that are most similar
In the assignment you will

Gain intuition for different notions of similarity and practice finding similar documents.
Explore the tradeoffs with representing documents using raw word counts and TF-IDF
Explore the behavior of different distance metrics by looking at the Wikipedia pages most similar to President Obama’s page.
Note to Amazon EC2 users: To conserve memory, make sure to stop all the other notebooks before running this notebook.


Locality Sensitive Hashing
Locality Sensitive Hashing (LSH) provides for a fast, efficient approximate nearest neighbor search. The algorithm scales well with respect to the number of data points as well as dimensions.

In this assignment, you will

Implement the LSH algorithm for approximate nearest neighbor search
Examine the accuracy for different documents by comparing against brute force search, and also contrast runtimes
Explore the role of the algorithm’s tuning parameters in the accuracy of the method


Latent Dirichlet Allocation for Text Data
In this assignment you will

apply standard preprocessing techniques on Wikipedia text data
use GraphLab Create to fit a Latent Dirichlet allocation (LDA) model
explore and interpret the results, including topic keywords and topic assignments for documents
Recall that a major feature distinguishing the LDA model from our previously explored methods is the notion of mixed membership. Throughout the course so far, our models have assumed that each data point belongs to a single cluster. k-means determines membership simply by shortest distance to the cluster center, and Gaussian mixture models suppose that each data point is drawn from one of their component mixture distributions. In many cases, though, it is more realistic to think of data as genuinely belonging to more than one cluster or category - for example, if we have a model for text data that includes both "Politics" and "World News" categories, then an article about a recent meeting of the United Nations should have membership in both categories rather than being forced into just one.

With this in mind, we will use GraphLab Create tools to fit an LDA model to a corpus of Wikipedia articles and examine the results to analyze the impact of a mixed membership approach. In particular, we want to identify the topics discovered by the model in terms of their most important words, and we want to use the model to predict the topic membership distribution for a given document.