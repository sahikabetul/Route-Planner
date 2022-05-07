# Route Planner with A* Search Algorithm
##  Udacity Data Structures and Algortihms Nanodegree

A* search is a graph traversal and path search algorithm, which is often used in many fields of computer science due to its completeness, optimality, and optimal efficiency. 

![delivery-route-planners-fleet](https://user-images.githubusercontent.com/54595314/167255491-f7ae56a2-4afb-4828-a162-f127f5c4696c.png)

One major practical drawback is its O(b^d) space complexity, as it stores all generated nodes in memory. Thus, in practical travel-routing systems, it is generally outperformed by algorithms which can pre-process the graph to attain better performance, as well as memory-bounded approaches; however, A* is still the best solution in many cases.

In this project, I built the A* route-planning algorithm -like the one used in Google Maps- to calculate the shortest path between two points on a map.

## Libraries Used

```
import networkx as nx
import pickle
import plotly.plotly as py
import random
from plotly.graph_objs import *
from plotly.offline import init_notebook_mode, plot, iplot
```

## Files in the Repository

- **Route Planner.ipynb:** the notebook of the project includes A* search algorithm.
- **helpers.py:** containing helper functions for initializing map, loading map and showing map.
- **map-10.pickle:** containing 10-point map.
- **map-40.pickle:** containing 40-point map.
- **test.py:** containing correct answers for testing code in 'Route Planner.ipynb' file.
