<h1 align="center">Analysis of A* Search on Minneapolis City Map</h1>

<p align="center"><strong>Description</strong>
<br> This project is part of an 5000 levelcourse, offered by <a href="https://www-users.cse.umn.edu/~gini/">Dr. Maria Gini</a> from the <a href="https://cse.umn.edu/cs">Dept. of CSE</a>, <a href="https://cse.umn.edu/">College of Sci. & Engg.</a>, <a href="https://twin-cities.umn.edu/">UMN</a> in Fall 2022<br/>

<div align="center"><img width="150" src="https://upload.wikimedia.org/wikipedia/commons/6/6a/University_of_Minnesota_Logo.svg"></div>

<h2>About</h2>
This study uses the Minneapolis map and four different heuristics to determine the pathways with the lowest costs. 
This is later extended to a few other cities with varying topologies. 
This paper employs informed search methods focusing on the A* search. 
We contrast the four heuristics in terms of use cases, temporal complexity, and spatial complexity.

<h2>Problem and Goal</h2>

To find the shortest path between two locations in Minneapolis City by considering its geographic information of roads 
and trying out various heuristics to the A* search algorithm. 
Our work suggests three distinct admissible strategies while considering building foundations for certain
user requirements. We identify 5 valid heuristics: basic (Euclidean, Manhattan, Chebyshev, and weighted
Euclidean) and realistic (weighted Euclidean based on one-way or two-way). Also, in order to explore
generalizability, we also apply the basic heuristics to maps for other locations. These 5 heuristics deploy
different ways of calculating the distance between two points, and we aim to find the optimal heuristic with
the lowest cost in time and memory complexity. We will research, test, and analyze them concerning A*
search and their effects on the best course of action.

<h2>Key learnings</h2>

- Pathfinding
  - Depth-First Search
  - Depth-Limited Search
  - Breadth-First Search
  - Best-First Search
  - Hill-Climbing Search
  - A* Search
  - IDA* Search
  - others
- Heuristics 
- Road maps and routes
- Plotting and visualization


<h2>Members</h2>
- <a href="https://www.linkedin.com/in/silaskati/">Kati, Silas</a> (MS Data Science, Dept. of CSE, CSE, UMN) | <a href="https://github.com/SilasKati">GitHub</a><br>
- Zhou, Moyan (Ph.D. Computer Science, Dept. of CSE, CSE, UMN)<br>
- Inaganti, Sai Tarun (MS Robotics, Robotics Institute, CSE, UMN)<br>


<h2>Future Works</h2>

There are mainly two directions for future work. 
<br><br>
On the one hand, our project is limited because we only used several regional maps to run the experiment, which
is a small portion of the world map. Therefore, to conclude that the result from our project is generalizable,
future work could apply the algorithms to maps of larger regions like counties or even whole states. However,
the study could limit to motorways alone by discarding the smaller highways, for example. If the result is
the same, we will be able to conclude that the results are generalizable, which is an essential consideration
in research.
<br>

On the other hand, our research serves as a foundation for the optimal heuristic for distance calculation;
future work could develop more sophisticated heuristics involving distance. For example, a realistic heuristic
that considers right turn and left turn can develop the heuristic based on the weighted Euclidean heuristic.
In this way, the innovative heuristic would be more likely to be optimal.


<h2>Copyright</h2>
This project is licensed under the terms of the MIT license.
