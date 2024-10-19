# Parallel

## Features
Hybrid Sorting: Uses Quick Sort and Insertion Sort based on sub-array size. <br>
Parallel Sorting: Employs MPI to distribute workload across multiple processes. <br>
Merge: Merges the sorted sub-arrays into a final sorted array. <br>

## Requirements
MPI Library: The code is designed to run using MPI. You will need an MPI implementation like OpenMPI or MPICH. <br>
C Compiler: A compiler such as GCC.

## Installation
Install MPI: sudo apt-get install openmpi-bin libopenmpi-dev <br>
Compile the Code using an MPI compiler: mpicc -o quicksort quicksort.c

## Usage:
### To execute the compiled program with a specified number of processes: <br>
`mpirun -np <number_of_processes> ./quicksort` <br>
`mpirun -np 4 ./quicksort`
