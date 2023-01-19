# Assignment 11, due January 24th 2023

The goal of this assignment is to implement two basic applications in the Chapel programming model.

## Exercise 1 (1.5 Points)

### Description

The Chapel programming model has been briefly discussed in the lecture. It is a high-level domain-specific language (DSL) that offers both shared and distributed memory parallelism.

### Tasks

- Download and install Chapel using [this download link](https://chapel-lang.org/download.html) and [this quickstart guide](https://chapel-lang.org/docs/usingchapel/QUICKSTART.html).
- Implement a parallel version of the Monte Carlo PI computation in Chapel and benchmark it for 1, 2, 4, and 8 threads on LCC2 with a problem size of 1 billion (10^9) samples.
- Implement a parallel version of matrix multiplication in Chapel and benchmark it for 1, 2, 4, and 8 threads on LCC2 with a problem size of 2552x2552.
- Enter your results for 8 threads into the comparison spreadsheet: https://docs.google.com/spreadsheets/d/1E-9kRGMV8Py1Qp32wuVHs7dWSXIWigBHc3Ba1iTheFc/edit

## Exercise 2 (1.5 Points)

### Tasks

- If you haven't already done so, extend your Chapel installation to support distributed memory parallelism using [this guide](https://chapel-lang.org/docs/usingchapel/multilocale.html#readme-multilocale). Examples of environment variables to be used on LCC2 when compiling Chapel are `CHPL_LAUNCHER=gasnetrun_mpi` and `CHPL_COMM_SUBSTRATE=mpi`. You can then re-compile your Chapel programs and launch them directly by running `./chapel_program -nl <number_of_locales>` using a job submission script.
- If you haven't already done so, extend your Chapel programs to support distributed memory parallelism.
- Benchmark your distributed memory version for 1, 2, and 4 nodes on LCC2 using 8 threads and enter your results into the comparison spreadsheet: https://docs.google.com/spreadsheets/d/1E-9kRGMV8Py1Qp32wuVHs7dWSXIWigBHc3Ba1iTheFc/edit
