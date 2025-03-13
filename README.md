# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
#Program to find the solution for the given linear equations.

#Developed by: MAGESH BOOPATHI.M

#RegisterNumber:212224230145
```python
import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
result=np.linalg.solve(A,B)
print(result)
```


## Output:

![Screenshot 2025-03-13 081207](https://github.com/user-attachments/assets/8d385abe-2179-48f8-89d3-0bf05aeb9f14)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

