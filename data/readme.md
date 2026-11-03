This folder holds benchmarks for continuous multi-agent path finding.
Each instance has a set number of agents in a set environment and contains 4 files:
- starts = start positions of all agents
- goals = goal positions of all agents
- param = configuration of agents (global, contains params such as agent radius)
- obstacles - in the continuous environment, obstacles are represented by polygons (here they are rectangles). Each obstacle is a 4-tuple (x-coordinate, y-coordinate, width, height)
