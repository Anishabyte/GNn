# Gnn
1.The following repository contains the code for calculating betweenness and closeness for approximation of node ranking.
2.Betweenness and closeness centrality are two commonly used node ranking measures.
3.A high value of these centrality indicate that majority of the information pass through these node.
4.In the model we are taking the shortest path for message aggregation.
5.we multipy the embedding lookup and adjacency matrix calculated using shortest path.
6.For loss we are taking margin loss.
7.Then we put it under multiple MLP layer and calculate the predicted betweenness score
8.For evaluation of node ranking we calculated KT score .
9.We tried the model with 5000 to 10000 nodes but it can be used for more number of nodes according to the the system .
10.This is an implementation of a Research paper by  Sunil Kumar Marya of Tokyo Institute of Technology.

