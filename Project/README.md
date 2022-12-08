Matrix Multiplication Kernel
======================

**Texas Tech University, CS5375 Computer Systems Organization and Architecture, Project**

*Bhuvana Keerthi Marri
  * R# 11779544.
  * TTU e-mail: bmarri@ttu.edu.

### Analysis of all the Parts of the Programming Project
Run the following commands:
For CPU execution:
g++ matrixMul_cpu.cpp -o matrixMul.exe

For GPU execution:

nvcc part_1.cu -o part_1.exe
nvprof ./part_1.exe

 Similarly for all the the Parts i.e. Part_2, Part_3, Part_4 run the above commands (line 17, 18).

