# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get n variable from the user
### Step 2: 
Get the input
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the values it would be interchanged
### Step 6: 
End the program

## Program:
```
#Program to circulate N values.
#Developed by:Matheswaran k
#RegisterNumber:212222110024
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:

![circulte](https://user-images.githubusercontent.com/119477782/228428433-d5ffbf75-f833-40b0-a4aa-db95170495fa.png)

## Result:
Thus the circulation of the n variables successfully found

