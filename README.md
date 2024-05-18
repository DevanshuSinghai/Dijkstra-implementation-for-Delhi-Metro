# Dijkstra implementation for Delhi Metro
This is the our first semester project which we do in accordance to our syllabus in Discrete Mathematics under the guidance of our supportive and helpful teachers
In this project my team has 4 memebers : 
- [@Pktiwari12](https://github.com/Pktiwari12)
- [@Sachin-Yadav2006](https://github.com/Sachin-Yadav2006)
- [@utkarsh-0026](https://github.com/utkarsh-0026)
- and me :relaxed:

  
Dijkstra’s algorithm is a famous technique for finding the shortest path between nodes in a graph. It can be applied to various real-world problems, tofind the optimal route between two points.
In this project we delves into the application of Dijkstra's Algorithm to enhance the efficiency of metro routing. By leveraging this algorithm, we aim to compute the optimal time andpaths between metro stations, ultimately minimizing travel time and improving the overall metro experience for passengers.


HOW DOES THE ALGOITHM WORK ??

1. The algorithm works by starting from a source node and assigning a tentative distance to every other node in the graph. The tentative distance is the current best estimate of the shortest distance from the source to that node. Initially, the tentative distance of the source node is zero, and the tentative distance of every other node is infinity, meaning that we don’t know how far they are from the source yet.

2. The algorithm then repeatedly selects the node with the smallest tentative distance and updates the tentative distances of its neighbors. To update the tentative distance of a neighbor, the algorithm adds the distance of the edge between the current node and the neighbor to the tentative distance of the current node, and compares it with the existing tentative distance of the neighbor. If the result is smaller, the algorithm replaces the tentative distance of the neighbor with the result. This means that the algorithm has found a shorter path to the neighbor.

3. The algorithm stops when it reaches the destination node, or when it has visited all the nodes that are reachable from the source. The final tentative distance of the destination node is the shortest distance from the source to the destination. The algorithm can also reconstruct the shortest path by tracing back the nodes that led to the destination

This is the visual representation of the above explaination

![alt text](/explaination_images/image.png)

![alt text](/explaination_images/image-1.png)
