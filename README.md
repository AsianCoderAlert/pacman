# pacman

This is Homework 1 from CSE 3521 at OSU.
Pacman mainly focuses on DFS, BFS, and Astar searching algorithms. 

Here is the route pacman picks based on DFS
![name](https://github.com/AsianCoderAlert/pacman/blob/master/img/DFS.gif)

Here is the effect of BFS. I am supposed to use collection deque as data 
structure in this implementation, but I ended up with sticking to list
structure. By always inserting into the first index of list, it did work
as an FIFO structure. However, it also took linear time to move on all the
rest elements in list.
![name](https://github.com/AsianCoderAlert/pacman/blob/master/img/BFS.gif)

A* search algorithm uses f(n) = g(n) + h(n) which evaluates the total costs
by adding the current costs up with estimate costs.
![name](https://github.com/AsianCoderAlert/pacman/blob/master/img/Astar.gif)
