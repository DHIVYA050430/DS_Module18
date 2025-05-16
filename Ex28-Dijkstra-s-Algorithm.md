Ex 6(C) Dijkstra’s Algorithm
## DATE: 14/05/2025
## AIM:
To write a C Program to implement Dijkstra's Algorithm to find the shortest path

## Algorithm
1. Start 
2. Read the number of vertices n and the adjacency matrix G representing the graph. 
3. Read the starting node u for Dijkstra's algorithm. 
4. Create the cost matrix where each G[i][j] is copied, and replace 0 values with infinity 
(except for the diagonal). 
5. Initialize the distance, pred, and visited arrays. 
6. For each node, find the one with the minimum distance that hasn't been visited. Update the 
distances and predecessors of its unvisited neighbors. 
7. Repeat the process until all nodes are visited. 
8. After the algorithm completes, print the shortest distance from the start node to each node 
and the path taken to reach each node. 
9. End

## Program:
```
/*
Program to implement Dijkstra's Algorithm 
Developed by: DIVYA E
RegisterNumber: 212223230050
*/
#include<stdio.h> 
#define INFINITY 9999 
#define MAX 10 
