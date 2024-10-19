# Parallel

Features
Hybrid Sorting: Uses Quick Sort and Insertion Sort based on sub-array size.
Parallel Sorting: Employs MPI to distribute workload across multiple processes.
Merge: Merges the sorted sub-arrays into a final sorted array.
Requirements
MPI Library: The code is designed to run using MPI. You will need an MPI implementation like OpenMPI or MPICH.
C Compiler: A compiler such as GCC.
Installation
Install MPI: sudo apt-get install openmpi-bin libopenmpi-dev
Compile the Code using an MPI compiler: mpicc -o quicksort quicksort.c
