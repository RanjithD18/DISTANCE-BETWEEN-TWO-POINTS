# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Get the input for list 1 and 2
### Step 3: 
Substitute the values in the distance formula  
![formula](https://github.com/RanjithD18/DISTANCE-BETWEEN-TWO-POINTS/blob/main/formula.JPG?raw=true)
### Step 4: 
Print the distance
### Step 5: 
End the program
### PROGRAM:
~~~
#Program to find the distance between two points.
#Developed by: Ranjith D
#RegisterNumber: 21500662
import numpy as np
l1=[10,6]
l2=[4,2]
distance=np.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))
print("{:.2f}".format(distance))
~~~
  


### OUTPUT:
![output](https://github.com/RanjithD18/DISTANCE-BETWEEN-TWO-POINTS/blob/main/Screenshot%20(25).png?raw=true)


### RESULT:
Thus the distance is successfully calculated
