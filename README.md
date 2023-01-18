# CIA-1

![Screenshot_20230118_050832](https://user-images.githubusercontent.com/55921648/213089701-e23ea087-32ea-430b-bcc5-3e57478ec984.png)







*******************************PRIMS METHOD**********************************
Prim's and Kruskal's algorithms are both used to find the minimum spanning tree (MST) of a graph.

Prim's algorithm starts with an arbitrary vertex and grows the MST by adding the vertex with the lowest weight edge to the MST and repeating the process until all vertices are included in the MST.

Kruskal's algorithm starts with an empty MST and grows it by adding edges with the lowest weight that do not form a cycle, until all vertices are included in the MST.

Both algorithms are greedy algorithms, meaning they make the locally optimal choice at each step with the hope of finding a global optimum.

Prim's method is generally faster for dense graph, while Kruskal's method is faster for sparse graphs.

Prims Method 

1.
     According to this graph, this is a directed graph.
According to the concept, the prims graph wont work on Directed Weighted Graph but in this scenario prims method works because in this graph while using prims method after E node the nodes doesnt go to D node which omits the -5 which satisfies the Prims Method 



 ![Screenshot_20230118_050623](https://user-images.githubusercontent.com/55921648/213090801-84b96322-0c91-4c66-8137-f19ad5977653.png)


Note :
       Prims only works for this scneario graph and its not applicable for any other Generic Directed Weighted Graph
       
       
       
  
  
*********************************KRUSKAL METHOD*******************************************
2.Kruskal's algorithm is a well-known method for finding the minimum spanning tree in an undirected, weighted graph. The algorithm works by sorting the edges in the graph by weight and then iteratively adding edges to the minimum spanning tree while maintaining the property that the tree remains a valid connected graph.

However, Kruskal's algorithm is not applicable to directed weighted graphs because it relies on the property that the graph is undirected. In a directed graph, the edges have a direction, and the minimum spanning tree would be different from an undirected graph. Additionally, Kruskal's algorithm does not take into account the direction of the edges when building the minimum spanning tree, which is essential for directed graphs.

A different algorithm, such as Dijkstra's algorithm or Bellman-Ford algorithm, would be needed to find the shortest path in a directed weighted graph.


Since this graph has negative node and its a directed graph kruskal doesnt satify the Grpah

![Screenshot_20230118_053829](https://user-images.githubusercontent.com/55921648/213094052-2380f4df-e2bf-4ccb-9e44-b1326ef31f66.png)

NOTE : Prims Doesnt work for Directed Graphs only bellman Ford is applicable for Directed Graph



***********************************DIJKSTRA METHOD*********************************
3. Dijkstra's algorithm is designed for use on graphs with non-negative edge weights, and it finds the shortest path from a single source vertex to all other vertices in the graph. However, it doesn't work on directed graph as it's based on the assumption that the shortest path to a vertex can only be reached by traversing edges with non-negative weights and that the shortest path to a vertex can be determined by relaxing edges in a specific order. This assumption is not always true for directed graphs, where edges can have negative weights, and the shortest path to a vertex may not be determined by relaxing edges in a specific order.

![Screenshot_20230118_055257](https://user-images.githubusercontent.com/55921648/213095498-90f71c84-7eba-4aa8-a9a0-b0a556c7ba54.png)






NOTE : Since Djk doesnt work for negative Edge Widgets it doesnot satisy the Graph so Bellman Ford can only be used




       
       
      
      
      
     

       
      



