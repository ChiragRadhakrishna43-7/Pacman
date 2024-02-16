# Pacman
Implementation of different search algorithms for the Pacman game.

<p align="justify">Credit for the code goes to http://ai.berkeley.edu.<br/><b>Attribution Information:</b> The Pacman AI projects were developed at UC Berkeley.<br/>
# The core projects and autograders were primarily created by John DeNero (denero@cs.berkeley.edu) and Dan Klein (klein@cs.berkeley.edu).<br/>
# Student side autograding was added by Brad Miller, Nick Hay, and Pieter Abbeel (pabbeel@cs.berkeley.edu).</p>

<p align="justify">To run and play the Pacman Game, type the following command in the Anaconda terminal:<br/></p>

# Python Pacman Game

To run the Python Pacman game, use the following command:

<details>
<summary>Click to reveal the command</summary>

```bash
python pacman.py
```
</details>

<p align="justify"> Two specific search algorithms implemented are: <br/>1. Breadth First Search (BFS) <br/>2. A Star Search (A*)</p>

<p align="justify"> To run Breadth First Search (BFS) Algorithm, use the following commands:</p>

python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5

<p align="justify"> To run A* Algorithm, use the command below. By default, the heuristic function is nullHeuristic. You can set the heuristic function to manhattanHeuristic by specifying the heuristic parameter during run time.</p>

python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic 
