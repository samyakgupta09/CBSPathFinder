# CBSPathFinder

In this project, I find optimal paths in video game maps with multiple agents using Conflict Based Search (CBS).

## Problem Setting
* The project works with grid based video game maps. 
* Each agent can move in the cardinal directions(north, south, east, west), each costing 1.0.
* A search problem consists of a video game map, k agents and a start and goal location for each agent.
* The goal is to find a path from the start till the goal location for each agent while minimizing the sum of cost of every path.

## Implementation
* The program finds optimal path for a number of different problems. Having different number of agents with different start and goal locations. 
* It uses CBS for each of these problems. We further use A* to find optimal path for an individual agent.
* Returns the optimal path for each agent while minimizing the sum of cost of paths. 

## Tech Stack
* Python
* Libraries used: copy, heapq, math, numpy, random

## Algorithms Used
* Conflict Based Search
* A* (Heuristic used: Manhattan Distance)

## How to run 
* To change the map, change line 27 in main.py to the file path for the map.
* To change the start and goals for the agents edit "test-instances/test_problems_den009d.txt"
