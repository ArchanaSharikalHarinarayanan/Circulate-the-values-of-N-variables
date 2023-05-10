# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define the user defined function name circulate()
### Step 2: 
Declare the variable to store the value given by  the user 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Assign the print statement 
### Step 6:
Print the program to get the output 

## Program:
```
#Program to circulate N values.
#Developed by: Santhosh L
#RegisterNumber: 212222100046
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![Screenshot (3)](https://github.com/sandy29l/Circulate-the-values-of-N-variables/assets/123359969/1ec76320-7b24-4604-a1f6-b7c3e55eefee)

## Result:
Thus the python program for circulating the values of n variables is executed successfully
