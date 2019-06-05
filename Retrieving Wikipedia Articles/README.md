## Nearest Neighbors
When exploring a large set of documents -- such as Wikipedia, news articles, StackOverflow, etc. -- it can be useful to get a list of related material. To find relevant documents you typically

Decide on a notion of similarity
Find the documents that are most similar
In the assignment you will
Gain intuition for different notions of similarity and practice finding similar documents.
Explore the tradeoffs with representing documents using raw word counts and TF-IDF
Explore the behavior of different distance metrics by looking at the Wikipedia pages most similar to President Obama’s page.

Locality Sensitive Hashing
Locality Sensitive Hashing (LSH) provides for a fast, efficient approximate nearest neighbor search. The algorithm scales well with respect to the number of data points as well as dimensions.
Implement the LSH algorithm for approximate nearest neighbor search
Examine the accuracy for different documents by comparing against brute force search, and also contrast runtimes
Explore the role of the algorithm’s tuning parameters in the accuracy of the method


