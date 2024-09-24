# Gnn  
* The following repository contains the code for calculating betweenness and closeness for
   approximation of node ranking.
* Betweenness and closeness centrality are two commonly used node ranking measures to find the 			most influential nodes in the graph in terms of information spread and connectivity.
* A higher value of the centrality for a node means this node lies on many shortest path.
* high value of these centrality indicate that majority of the information pass through these node.
* In the model we are taking the shortest path for message aggregation.
* The benefit of out model is that it is inductive which means it can be trained on one set of  
  graph and evaluated on another set of graph.
* For the model we are using GNN Bet and GNN close for approximating betweenenss and closeness 
  centrality.
* we multipy the embedding lookup and adjacency matrix calculated using shortest path.
* For loss we are taking margin loss.
* Then we put it under multiple MLP layer and calculate the predicted betweenness score
* For evaluation of node ranking we calculated KT score .
* We tried the model with 5000 to 10000 nodes but it can be used for more number of nodes 
  according to the the system .
* This is an implementation of a Research paper by  Sunil Kumar Marya of Tokyo Institute of 
  Technology.

