# Particle Swarm Optimization (PSO) 

## Overview

This code implements a Particle Swarm Optimization (PSO) algorithm in Python. PSO is a population-based optimization algorithm inspired by the social behavior of birds flocking or fish schooling. The goal of this PSO implementation is to optimize two different mathematical functions, denoted as `f` and `g`. The code simulates a swarm of particles that search for the global minimum and maximum of these functions in the solution space.

## Code Structure

The code is organized into several sections, each serving a specific purpose:

1. **Particle Class**:
    - The `particle` class represents a single particle in the PSO algorithm.
    - Each particle carries information about its position, velocity, and the cost (fitness) associated with its position.

2. **Particle Movement Functions**:
    - Two functions, `f_moves` and `g_moves`, define how particles move in the search space for functions `f` and `g`, respectively.
    - These functions implement the PSO update formula discussed in class, combining inertia, cognitive, and social components to update a particle's velocity and position.

3. **Mathematical Functions**:
    - Two mathematical functions, `f` and `g`, are defined in the code. These functions represent the objective functions to be optimized using PSO.
    - The `cost_f` and `cost_g` functions evaluate the cost (fitness) of a particle's position for functions `f` and `g`, respectively.
    - The code also initializes global variables to keep track of the best global positions and their costs found during optimization.

4. **Main Functions for Optimization**:
    - Two main functions, `main_f` and `main_g`, implement the PSO optimization process for functions `f` and `g`, respectively.
    - These functions initialize a swarm of particles, update their positions through iterations, and print the best global positions and their costs.

## Mathematical Functions

- `f` represents the first mathematical function to be optimized.
- `g` represents the second mathematical function to be optimized.
