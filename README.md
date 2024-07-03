# Gnn
The following repository contains the code for calculating betweenness and closeness for approximation of node ranking.
Betweenness and closeness centrality are two commonly used node ranking measures.
A high value of these centrality indicate that majority of the information pass through these node.
In the model we are taking the shortest path for message aggregation.
we multipy the embedding lookup and adjacency matrix calculated using shortest path.
For loss we are taking margin loss.
Then we put it under multiple MLP layer and calculate the predicted betweenness score
For evaluation of node ranking we calculated KT score .
We tried the model with 5000 to 10000 nodes but it can be used for more number of nodes according to the the system .
This is an implementation of a Research paper by  Sunil Kumar Marya of Tokyo Institute of Technology.

