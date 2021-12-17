# MAXIMAL CLIQUE PROBLEM
Given a small graph with N nodes and E edges, the task is to find the maximum clique in the given graph. A clique is a complete subgraph of a given graph. This means that all nodes in the said subgraph are directly connected to each other, or there is an edge between any two nodes in the subgraph. The maximal clique is the complete subgraph of a given graph which contains the maximum number of nodes.

#### ALGORITHM
Algorithm: Max-Clique (G, n, k) 
S := Φ 
for i = 1 to k do 
   t := choice (1…n)  
   if t Є S then 
      return failure 
   S := S ∪ t  
for all pairs (i, j) such that i Є S and j Є S and i ≠ j do 
   if (i, j) is not a edge of the graph then  
      return failure 
return success 
