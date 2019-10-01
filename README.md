## AI  

**Clustering MST**

Clustering module based on the Minimum Spanning Tree Algorithm.

- A weighted complete graph is computed, consisting in all the photos that need to be clustered. The edges' weights are computed based on a given image distance function. 
- Starting from this graph, the minimum spanning tree algorithm is applied. 
- From the obtained tree, the first n edges with the greatest weights are eliminated.
- The connected components left in the tree are the desired clusters.

<br>

**Cross-in-Tray Function**

Evolutive Algorithm that computes the minimum of the Cross-in-Tray function.
