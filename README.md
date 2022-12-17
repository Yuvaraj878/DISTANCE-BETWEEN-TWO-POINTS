# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
First assume that two variables as l1 and l2.
### Step 2: 
Then give the values for that variables as mentioned in the question.
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.jpg)
### Step 4: 
Then print that values,it shows many values after decimal to avoid that we should give {:.2f}
### Step 5: 
After finishing that we should push this into the git repository by giving the command git push -u origin main.
### PROGRAM:
import math

 l1=[4,2]

 l2=[10,6]

 a = math.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))

 print("{:.2f}".format(a))


### OUTPUT:


### RESULT:
The output for Distance between the two points is Successfull.