---
title: Recursion
---

## What ?
A way of solving a problem by having a function calling itself. 
- Performing the same operation with different inputs.
- In every step we make the problem smaller to arrive at the solution at the end
- We need a base condition to terminate the recursion to exit the loop of recursion
- Mostly used in 
	- Trees and Graph DS
	- Divide and Conquer, Greedy and Dynamic Programming Algos
## Why we need it ?
It helps to break down the problem into smaller ones and easier to use.
## When to Choose ?
- when we can divide the problem into similar sub problems.
- when extra overhead (Time and Space) is okay 
- quick instead of efficient
- when we are not sure on the end , tree traversal (its more efficient than an iteration)
- when we use memoization
## How it works ?
Recursion utilizes stack memory. When a function is called from within the function, the upper function is added to the stack memory until the lower function is executed. 
- In recursion , the stack memory follows Last In - First Out until the stack memory is empty. 
- **Stack memory available plays a vital role in recursion. if its the stack memory is less than the depth required, the program fails and crashes.**
- for a `recursive_method(n)`, this is how the stack memory is filled

| stack memory            |
| :---------------------: |
| `recursive_method(1)`   |
| `recursive_method(2)`   |
| `recursive_method(3)`   |
| .                       |
| .                       |
| .                       |
| `recursive_method(n-1)` |
| `recursive_method(n) `  |


## Recursion vs Iteration 
| Recursion                                                                                                   | Iteration                                                                                      |
| ----------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| Condition statement determines the termination and the number for recursions are only identified at the end | Control variable defines the fixed iteration before hand                                       |
| Infinite recursions causes system crash due to lack of memory                                               | Infinite iteration does not crash system but takes up the CPU power, hence **Space Efficient** |
| It requires time to push and pop from stack memory                                                          | Its **Time Efficient**                                                                         |
| Easy to code  | Not as easy as recursion |

## How to write recursion
Needs below three cases for the input to perform a recursion
#### Add Recursive Case 
- Understanding the flow of the solution to identify the recursive case in the solution
#### Add Base Case Condition  
- which terminates the recursion 
#### Add Unintentional case 
- the constrains for the function inputs


## Python - Recursion Limit
we can increase the recursion limit in python by 
- #todo - read more about it 

```python
import sys
sys.setrecursionlimit(n)
```

## Practice 
https://github.com/mohankumarpaluru/dsa-preperation/blob/main/Recursion.ipynb