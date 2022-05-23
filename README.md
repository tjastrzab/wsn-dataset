## A Randomized Algorithm for Wireless Sensor Network Lifetime Optimization

**Amit Dua, Zbigniew J. Czech, Tomasz Jastrzab**

This repository contains a dataset of sample Wireless Sensor Networks, used in the manuscript submitted to the 25th International Conference on Modeling, Analysis
and Simulation of Wireless and Mobile Systems 2022. 

#### Dataset structure

This dataset consists of 80 randomly generated problem instances. Each problem instance consists of two files containing the sets of sensors and targets, whose names end with *sensors.txt* or *targets.txt*, respectively.
 
The structure of each problem instance *sensor* file is as follows:
1. Each sensor is defined on a separate line. 
2. The consecutive lines consist of sensor id, X position, Y position, fixed 0 value (to be ignored), and sensing range.
3. The sensors were randomly plaed within a grid of size 500 x 500.

The structure of each problem instance *target* file is as follows:
1. Each target is defined on a separate line. 
2. The consecutive lines consist of target id, X position, and Y position.

Each file name encodes the number of sensors and the instance identifier (from a to e). The expected coverage level, expressed as a percentage, is encoded in the directory name, as a three-digit number, i.e. 100 (alpha = 1.00), 085 (alpha = 0.85), 075 (alpha = 0.75), and 050 (alpha = 0.50).