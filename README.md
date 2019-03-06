# 538_grid_maze
Jupyter Python notebook to recreate the grid maze from 538 Riddler

https://fivethirtyeight.com/features/can-you-escape-a-maze-without-walls/

First, created a two-dimensional array representing the maze. 
Then wrote functions to ...
- return a new x/y coordinate if given a curren x/y coordinate and a direction vector
- add two tuples together
- assign values to the "misc." squares in the maze
- traverse the maze starting from a given square. This function reads the current location in the maze, applies the correct changes to the direction vector, and then reads the result of the next square recursively. Will continue to print out events until you either leave the maze, land in lava, or reach the goal.

Winning Maze! code block
- Filled the maze with directions I had previously identified as working to reach the goal, and then traverses the maze starting from the correct perimeter square. The list of events shows how the program traversed through the maze.

Second code block
- Entered the same maze from each of the possible north/south perimeter squares. Shows the paths and results for each of the given inputs.
