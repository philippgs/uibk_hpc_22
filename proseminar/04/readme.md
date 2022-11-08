# Assignment 4 for November 15th 2022

The goal of this assignment is to optimize the heat stencil application.

## Exercise 1 (3 Points)

This exercise consists in profiling and analyzing the performance of the heat stencil application.

### Tasks

- Do a detailed performance analysis on your 2D (and optionally your 3D heat stencil implementation). Use either tools discussed in the lecture (`perf`, `gprof`, `gperftools`, etc.) or any tools you deem fit for generating a performance profile.
- Provide a report that discusses the most expensive source code locations ("hot spots") along with explaining why they are expensive and how to improve on that.
- Optionally consider improving your code using the information gathered in the previous tasks. If you do, document the improvement you managed to achieve.
- Insert the final walltime and speedup of at least the 2D stencil for 64 cores for N=2048x2048 and T=100 into the comparison spreadsheet: https://docs.google.com/spreadsheets/d/1E-9kRGMV8Py1Qp32wuVHs7dWSXIWigBHc3Ba1iTheFc/edit#gid=1075089851