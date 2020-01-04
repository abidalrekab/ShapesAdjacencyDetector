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
 We have two object which have their vertices in form of a list : [[[140,40],[180,100],[100,100]],[[100,100],[180,100],[180,160],[100,180]]]
![Fig1](Annotation%202020-01-04%20003205.png)


# Author : Mohamed Abidalrekab
# license : Free
# Year: 2020
