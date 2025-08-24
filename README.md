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
```
#Program to find the solution for the given linear equations.
#Developed by: DODLA SUSMITHA
#RegisterNumber: 212224110016
import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
result= np.linalg.solve(A,B)
print(result)
```


## Output:
<img width="1298" height="848" alt="Screenshot 2025-08-24 201731" src="https://github.com/user-attachments/assets/096af37e-c20f-4171-9c36-e3f5ec6d6e9a" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

