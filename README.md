# PathFinding

This is a piece of code that I wrote because I wanted to try out an assignment I found 
online when reading up on algorithms.
 
It is a method that implements an A* search algorithm to find and return the shortest 
path between two points in a 2-dimensional map.

The method takes a start and goal point, a pointer to a map as well as its height and width, 
a pointer to write the path to and the max amount of steps the path may take.

In the map traversable points are indicated by 1, and none-traversable by 0.

It either returns the amount of steps needed to reach the goal after writing the path to 
the pointer or -1 if it can not reach the goal.
