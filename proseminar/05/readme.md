# Assignment 5 for November 22nd 2022

The goal of this assignment is to optimize the heat stencil application.

## Exercise 1 (1 Point)

This exercise consists in comparing blocking and non-blocking communication for the heat stencil application.

### Tasks

- Provide an MPI implementation for the 1D heat stencil that uses non-blocking communication. If you already implemented a non-blocking version, provide a blocking version, but ensure the non-blocking version works as described below.
- Structure your program such that you 1) start a non-blocking ghost cell exchange, 2) compute the inner cells which do not require the result of the ghost cell exchange, 3) block until the ghost cell exchange has finished, and 4) compute the remaining cells.
- Run your programs with multiple problem and machine sizes and compare both versions.
- Insert the improvement for 64 cores over blocking communication for a problem size of your choice into the comparison spreadsheet: https://docs.google.com/spreadsheets/d/1E-9kRGMV8Py1Qp32wuVHs7dWSXIWigBHc3Ba1iTheFc/edit

## Exercise 2 (2 Points)

This exercise consists in comparing blocking and non-blocking communication for the heat stencil application.

### Tasks

- Provide an MPI implementation for the 2D or 3D heat stencil that uses non-blocking communication. If you already implemented a non-blocking version, provide a blocking version.
- Structure your program similarly as described in Exercise 1. Make sure you first post all non-blocking communication calls that are possible, then compute all cells that do not depend on the result of this communication, wait, and compute the remaining cells.
- Run your programs with multiple problem and machine sizes and compare both versions.
- Insert the improvement for 64 cores over blocking communication for a problem size of your choice into the comparison spreadsheet: https://docs.google.com/spreadsheets/d/1E-9kRGMV8Py1Qp32wuVHs7dWSXIWigBHc3Ba1iTheFc/edit