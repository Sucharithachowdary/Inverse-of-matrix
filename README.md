# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of a nested array

## ALGORITHM:
### Step 1:
import numpy module
### Step 2:
Declare a variables l1 and l2 as a empty list
### Step 3:
Get the input of the variables n and m
### Step 4:
Loop a variable i in the range of n and nest loop a variable j in range m
### Step 5:
Get the value of nump variables
### Step 6:
During the loop append the nump values to l1 and l1values to list l2
### Step 7:
Declare a variable value 1 and l2 by converting to an array
### Step 8:
Declare a variable inverse,using numpy module's linalg and inv functions find the inverse of l2
### Step 9:
Print the values of inverse

## PROGRAM:
import numpy as np
l1,l2 = [],[]
r,c=int(input()),int(input())
for i in range(r):
    for j in range(c):
        num=int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)
value1=np.array(l2)
inverse = np.linalg.inv(value1)
print(inverse)
## OUTPUT:
![image](https://user-images.githubusercontent.com/94166007/153748706-58d55290-6e69-49ec-bf44-b21d3204d964.png)

## RESULT:
Thus the program runs successfully
