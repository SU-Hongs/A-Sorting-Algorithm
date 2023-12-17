# Sorting and Performance Statistics Program
## Overview
This repository contains a C program written by Raymond Wong, used for experimental setup. It's designed to read data from a file, sort it using a simple sorting algorithm, and output the sorted data along with performance statistics and timing information.

## Repository Contents
- sort.c: The main C source code for the sorting program.
- config.txt: Configuration file for the program.
- data.txt: Input data file containing unsorted integers.
- output.txt: Output file containing sorted integers.
- stat.txt: Statistics file containing information about the number of swaps during sorting.
- time.txt: Time tracking file with execution time details (applicable for non-Windows systems).
## Program Description
- The program reads configuration settings and data from config.txt and data.txt, respectively.
- It then sorts the integers using a basic sorting algorithm.
- The sorted data is written to output.txt.
- Sorting statistics (number of swaps) are recorded in stat.txt.
- Execution time details are written in time.txt (non-Windows systems only).
## Configuration File Format (config.txt)
- Data filename (data.txt)
- Size of the data array
- Three additional parameters (1000, 2000, and 0.5 in the given example).
## Example Data File Content (data.txt)
10 8 5 2 3 7 6 2 4 1
## Compilation and Execution
1. Compile the program using a C compiler, e.g., gcc -o sort_program sort.c.
2. Run the compiled program, ./sort_program.
3. Check output.txt, stat.txt, and time.txt for the results.

## Technical Report
We upload the full technical report including every detail of our project as Sort.pdf.

## Citation
If you want to use our code, please cite as xxx.
