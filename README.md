# Ant colony with C+openMP

This project is the result an assignment for my MSc and the original purpose was solve the clasic travelling salesman problem used a simple ant colony system and compare the performance with only thread vs multithreading with openMP.

## Single core

The test with simple core was execute in a laptop with:
- Ubuntu 16.04
- Core I5
- 8gb ram DDR3

## OpenMP
The test with multithreading was execute in cluster of my university.

## Input
The imput for this code is the distance matrix. This matrix is array of *nxn* cities where register distance between cities.  

## Output
The distance of best ant for each iteration if best ant improve.

## To-DO
1. Pointer support
2. Calculate of distance matrix
3. Swarm intelligence
4. Comparative with exact algorithm like: lineal algorithm
