# Off-by-One Error in C Loop

This repository demonstrates a common off-by-one error in C programming. The code intends to print numbers 1 through 10, but contains a subtle error that leads to incorrect output.

## Description

The `bug.c` file shows a simple `while` loop designed to print numbers from 1 to 10.  However, the loop condition might cause it to either stop before reaching 10 or continue beyond 10.  This is a typical example of an off-by-one error often encountered in C programming.

## Solution

The solution is implemented in `bugSolution.c`.  It addresses the off-by-one error by carefully considering the loop condition and ensuring the loop iterates exactly the desired number of times.