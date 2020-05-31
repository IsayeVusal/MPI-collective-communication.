# MPI-collective-communication.
Parallel  matrix multiplication using Message passing interface collective communication.

comm.reduce - Data reduction involves reducing a set of numbers into a smaller set of numbers via a function. Similar to MPI_Gather, MPI_Reduce takes an array of input elements on each process and returns an array of output elements to the root process. The output elements contain the reduced result.

comm.Barrier() - Creates a barrier synchronization in a group. Each task, when reaching the Barrier() call, blocks until all tasks in the group reach a Barrier() call. Then all tasks are free to proceed.
