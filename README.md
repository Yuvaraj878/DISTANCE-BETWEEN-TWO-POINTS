# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
First assume that two variables as l1 and l2.
### Step 2: 
Then give the values for that variables as mentioned in the question.
### Step 3: 
Substitute the values in the distance formula  ![image](https://user-images.githubusercontent.com/118622554/208253297-afafe443-4ca9-4327-919f-eaee238ddacc.png)

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
file:///home/sec/Pictures/Screenshots/Ex%203.png![image](https://user-images.githubusercontent.com/118622554/208253742-781649c4-edbd-4c5d-adee-9419d3de30af.png)


### RESULT:
The output for Distance between the two points is Successfull.
