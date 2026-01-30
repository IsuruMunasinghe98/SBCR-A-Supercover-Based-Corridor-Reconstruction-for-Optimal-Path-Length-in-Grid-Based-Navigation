⚠️ **Note:** The associated paper describing this work is currently under review. The full codebase will be made publicly available after the paper has been accepted for publication.

# SBCR-A*: Supercover-Based Corridor Reconstruction for Optimal Path Length in Grid-Based Navigation

SBCR-A* is an improved A* reconstruction method that produces a compact sequence of straight, collision-free path segments using supercover-based line-of-sight (LOS) validation and obstacle-boundary-guided refinement.

## Overview

Grid-based planners such as **A\*** are widely used in robotics and autonomous navigation because many environments can be discretized into **binary occupancy grids**, guaranteeing a solution whenever a collision-free path exists. In practice, however, standard grid search often produces paths with **redundant waypoints**, **unnecessary turns**, and **stepwise motion artifacts**, which increase traversal time, energy consumption, and control effort. **SBCR-A\*** is a new A\*-based approach that integrates supercover line-of-sight validation and obstacle-boundary-guided refinement to reduce waypoint redundancy and produce a compact sequence of **straight** segments with improved **path-length optimality**, while preserving collision-freedom under a conservative occupancy-grid map.








