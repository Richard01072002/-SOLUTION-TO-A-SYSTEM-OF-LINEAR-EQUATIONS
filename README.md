# EXP-1 -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## date: 09.08.2023
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
#Developed by: richardson A
#RegisterNumber:23000803

import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b=np.array([-9,4,-1])
sol=np.linalg.solve(a,b)
print(sol)
```

## Output:

<img width="1440" alt="Screenshot 2023-09-25 at 1 26 45 PM" src="https://github.com/Richard01072002/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/141472248/ba53dcc9-25e1-418b-a168-76115dbc8c1f">


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

