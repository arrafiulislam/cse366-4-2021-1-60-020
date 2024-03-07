# Assignment 1: Dynamic Robot Movement Simulation
This project aims to develop an advanced simulation environment for a robot navigating through a dynamically created grid. The simulation incorporates fundamental programming concepts, object-oriented programming (OOP), navigation algorithms, task optimization, safety, and energy management strategies.

#Detailed Requirements
Environment Setup: Implement a class Environment that generates a 10x10 grid with dynamically placed obstacles, a start position, and an end position.

Robot (Agent): Implement a class Agent with movement capabilities, tracking of current position, and methods for managing energy levels and battery status. Battery management should include recharging when the battery level reaches 0%.

Simulation: Simulate the robot's movement through the grid, considering energy consumption and managing energy levels to complete tasks efficiently.

Pathfinding Algorithms: Implement Uniform Cost Search (UCS) and A* (A Star) pathfinding algorithms. Evaluate based on battery recharge frequency to determine the optimal algorithm.

Visualization: Use libraries like matplotlib to visualize the grid, obstacles, paths, and the robot's energy levels over time.

Task Optimization and Safety: Implement strategies to minimize travel time, energy consumption, and ensure safety by detecting and avoiding potential collisions.

Bonus (Optional): Explore advanced pathfinding algorithms and consider different terrain types affecting movement cost and energy consumption.

#Deliverables
GitHub Project Submission with a structured repository containing:
 -Jupyter notebook
 -Detailed report 
 -README.md files providing an overview and instructions for running the simulation
