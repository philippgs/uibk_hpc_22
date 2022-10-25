# Assignment 3 for November 25th 2022

The goal of this assignment is to extend the heat stencil application and measure its performance.

## Exercise 1 (1.5 Points)

This exercise consists in extending the heat stencil application of Assignment 2 to two dimensions.

### Tasks

- Extend the heat stencil application to the two-dimensional case and name it `heat_stencil_2D`.
- Provide a sequential and an MPI implementation, and for the latter make use of MPI's virtual topologies and derived data types features where applicable. Try to make your implementation as efficient as possible, also with regard to code readability.
- Run your programs with multiple problem and machine sizes and measure speeup and efficiency. Consider using strong scalability, weak scalability, or both. Justify your choice.
- Illustrate the data in appropriate figures and discuss them. What can you observe?
- Measure and illustrate at least one domain-specific and one domain-inspecific performance metric. What can you observe?
- How can you verify the correctness of your applications?
- Insert the (absolute) scalability for 64 cores for a problem size of your choice into the comparison spreadsheet: https://docs.google.com/spreadsheets/d/1E-9kRGMV8Py1Qp32wuVHs7dWSXIWigBHc3Ba1iTheFc/edit?usp=sharing

## Exercise 2 (1.5 Points)

This exercise consists in extending the heat stencil application of Assignment 2 to three dimensions.

### Tasks

- Repeat all tasks of Exercise 1, but this time for the three-dimensional case.
- Insert the (absolute) scalability for 64 cores for a problem size of your choice into the comparison spreadsheet: https://docs.google.com/spreadsheets/d/1E-9kRGMV8Py1Qp32wuVHs7dWSXIWigBHc3Ba1iTheFc/edit?usp=sharing