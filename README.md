# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1
Import the NumPy library to use its built-in linear algebra tools.
## Step 2
Define the coefficient matrix and the constant matrix using np.array().
## Step 3
Solve the system of linear equations using np.linalg.solve().
## Step 4
Print the solution to display the values of the variables.
## Step 5
End the program.
## Program:
```python
#Program to find the solution for the given linear equations.
#Developed by: Abheek.A
#RegisterNumber:212224100001
import numpy as np
A = np.array([[1, -3], [3, 1]])  
B = np.array([0, 10])            
solution = np.linalg.solve(A, B)
print(solution)

```
## Output:
![Screenshot 2025-04-25 113336](https://github.com/user-attachments/assets/fc2d382e-eded-44d1-a873-e7fe17cabf36)
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

