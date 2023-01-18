# Sem4Cat1
Prim's Algorithm : 
For the prim's algorithm we take the minimum cost edge in the start and then we select the next minimum cost edge but this time we have to choose one connected to the already included edges. If this is done for the question given then we end up with E---(-5)---->D and since these two vertices have no outgoing edges we cannot move forward from here.

Kruskal's Algrorithm : 
For the kruskal's algrorithm we have to start with the minimum edge and continue in ascending order and we discard any edge that leads to the formation of a loop or cycle. Following the rules of kruskal's algorithm we end up with a graph that is almost similar to the graph in the questin just that the edge connecting B to C with edge weight 3 is missing. 

Dijkstrak's Algorithm : 
Using dijkrak's algorithm we get : A--(2)-->C--(1)-->B--(3)-->E--(-5)-->D.

In conclusion of the two results we get that do connect the vertex A to all the others Dijkrak's is the better option as for kruskal's too only in this case everything was connected, but in other directed graphs it is not necessary that it may happen that a minimum spanning tree can be created. 
                             
