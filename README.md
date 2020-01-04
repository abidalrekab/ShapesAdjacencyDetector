# ShapesAdjacencyDetector

This program to detect whether two polygons shapes are adjacent, touching, or overlapped.This functionality is part of a package BLOCKSWORLD.

# This package checks four possible cases: #

- Case 1: Objects Touching. there are two objects ( polygons ) touch each other via a vertex and an edge.
- Case 1-1: Objects Touching. there are two objects ( polygons ) touch each other at a vertex.
- Case 2: Objects adjacent. there will be an object shares two vertices with another object but without overlapping.
- Case 3: Objects partially Overlapped. in this case two similar objects (polygons) are overlapped
- case 3-1: objects partially overlapped. in this case two different objects ( both differ in number of vertices ) are overlapped
- case 4: objects Fully overlapped.in this case two different objects ( both differ/same in number of vertices ) are overlapped. yet this case is different because we can have two object are centered at a very close position.      



#Test case:#
 We have two object which have their vertices in form of a list :  [[[10,40],[40,10],[40,70]],[[40,10],[70,10],[70,70]]]
![Fig1](Annotation%202020-01-04%20003205.png)
As in case 1 in figure 1. running the program by appropriately renaming or just choosing points6 to be points so that program understand that we have two objects and we want to check them. 
**Results**
![Fig2](Annotation%202020-01-04%20011812.png)

# Author : Mohamed Abidalrekab
# license : Free
# Year: 2020
