### Name
Hayato Waki

### ID
920753948

### How many hours
8 hours

## A brief description
### Question 1
First, I calculated the distance between pacman and food. Next, I calculated the distance between pacman and ghost.
At the same time, I got proximity. Then I arranged score using those distances.

### Question 2
If agent is equals to 0, return max of successors of agent. If not, increment agent number and measure if the agent
number is equals to original number of successors of agent. Then, return min of successors of the agent.

### Question 3
I created three functions to split by depth. In max_value(), get max of successors of agent which is v. Then if v is
bigger than b, return v. In min_value(), get min of successors of agent which is v this time. Then if v is smaller
than a, return v. In alphabeta(), if agent is equals to 0, return max_value(). if not, return min_value().

### Question 4
Expectimax is almost same as minimax. One different point is that return the average of values of agent's successors.

### Question 5
I'm not sure about it to be honest. So I just copied evaluationFunction in ReflexAgent class.