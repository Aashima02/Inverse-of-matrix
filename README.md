# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of a matrix.

## ALGORITHM:
### Step 1:
Import Numpy module as np.
### Step 2:
Create empty lists.
### Step 3:
Get input from the user for number of rows and columns.
### Step 4:
Use nested lists to append list.
### Step 5:
Print the inverse of the array using np.linalg.inv


## PROGRAM:
```
To write a python program to find the inverse of a matrix.
Developed by:  Aashima Nazreen Sayeed S
Register Number: 21500368

import numpy as np
rows=int(input())
columns=int(input())
l1=[]
for i in range(rows):
    temp=[]
    for j in range(columns):
        t=int(input())
        temp+=[t]
    l1+=[temp]
print(l1)
print(np.linalg.inv(l1))
```

## OUTPUT:
![inverse](https://user-images.githubusercontent.com/93427086/153589122-74157be6-accb-4ddf-9b4b-a1ae10082321.png)

## RESULT:
Thus a program is written to find the inverse of the matrix.
