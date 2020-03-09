Name: Hayato Waki
ID: 920753948
The length of time I spent for this assignment: 10 hours

## Description
### Q1
By using Stack for frontier, I could implement depth first search algorithm.

### Q2
By using Queue for frontier, I could implement breadth first search algorithm. But, as a difference from q1, I expanded node in the
successor cycle.

### Q3
Almost same as bfs. But, I initialized frontier using Priority Queue with action cost as well as starting position.

### Q4
Almost same as UCS. But, when I pushed un-visited node into frontier, the cost of that includes heuristic of the node.

### Q5
First of all, I defined a list for hold corners. And I could judge if the position is goal or not by judging if it is included in
default corners and it's not included in the list of hold corners. Also by using the same algorithm, I could implement getSuccessors method.

### Q6
In order to calculate heuristic, I used the manhattan heuristic.

### Q7
I tried. but I didn't figure it out.

### Q8
To find path to closest dot, I used BFS. And the goal state boolean is the same as if food is there or not.
