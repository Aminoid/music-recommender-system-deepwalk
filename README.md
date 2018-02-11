## Graph Embeddings for Recommender Systems

Develop a Recommender System predicting user's preference for some item not yet rated. using a graph based technique called DeepWalk.

## Procedure
1. Create a heterogeneous information network with nodes consisting of users,
itemratings, items, and other entities related to those items
2. Use DeepWalk to generate random walks over this graph
3. Based on these random walks, embed the graph in a low dimensional space using word2vec.

## Datasets
Several movie datasets located in the data folder. This folder includes a
usermovie ratings dataset, given in a training and test set, as well as other data files containing information about the movies, such as the actors, directors, and genres.

## How to run
`python -m rec2vec --walk-length 2 --number-walks 2 --workers 4`
