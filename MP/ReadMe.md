# CLIQUE
A clique is a subgraph of a graph G that is complete.

## MAXIMAL CLIQUE PROBLEM
Given a small graph with N nodes and E edges, the task is to find the maximum clique in the given graph. A clique is a complete subgraph of a given graph. This means that all nodes in the said subgraph are directly connected to each other, or there is an edge between any two nodes in the subgraph. The maximal clique is the complete subgraph of a given graph which contains the maximum number of nodes.

#### ALGORITHM
Algorithm: Max-Clique (G, n, k) </br>
S := Φ </br>
&ensp;&ensp; for i = 1 to k do </br> 
&ensp;&ensp; t := choice (1…n) </br>
&ensp;&ensp; if t Є S then  </br>
&ensp;&ensp;&ensp;&ensp; return failure </br>
&ensp;&ensp; S := S ∪ t  </br>
for all pairs (i, j) such that i Є S and j Є S and i ≠ j do </br>
&ensp;&ensp; if (i, j) is not a edge of the graph then </br>
&ensp;&ensp;&ensp;&ensp; return failure </br>
return success </br>

## REFERENCES
1. GeeksforGeeks.(2021). Maximal Clique Problem. https://www.geeksforgeeks.org/maximal-clique-problem-recursive-solution/
