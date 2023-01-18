# CIA-1

Prim's and Kruskal's algorithms are both used to find the minimum spanning tree (MST) of a graph.

Prim's algorithm starts with an arbitrary vertex and grows the MST by adding the vertex with the lowest weight edge to the MST and repeating the process until all vertices are included in the MST.

Kruskal's algorithm starts with an empty MST and grows it by adding edges with the lowest weight that do not form a cycle, until all vertices are included in the MST.

Both algorithms are greedy algorithms, meaning they make the locally optimal choice at each step with the hope of finding a global optimum.

Prim's method is generally faster for dense graph, while Kruskal's method is faster for sparse graphs.

Prims Method 

1.
     ![Screenshot_20230118_050832](https://user-images.githubusercontent.com/55921648/213089701-e23ea087-32ea-430b-bcc5-3e57478ec984.png)

According to this graph, this is a directed graph.
According to the concept, the prims graph wont work on Directed Weighted Graph but in this scenario prims method works because in this graph while using prims method after E node the nodes doesnt go to D node which omits the -5 which satisfies the Prims Method 



 ![Screenshot_20230118_050623](https://user-images.githubusercontent.com/55921648/213090801-84b96322-0c91-4c66-8137-f19ad5977653.png)


Note :
       Prims only works for this scneario graph and its not applicable for any other Generic Directed Weighted Graph
       
       
      
      
      
     

       
      



