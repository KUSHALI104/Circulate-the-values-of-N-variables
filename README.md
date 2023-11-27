# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: start the program 
### Step 2: get into the input from the user usind eval(input())
### Step 3: Get the value from the user for the number of rotation
### Step 4: Using the slicing concept rotate the list
### Step 5: using concentration operation display the entire rotated list
### Step 6: stop the program
## Program:
```
#Program to circulate N values.
#Developed by: kusali p g
#RegisterNumber:23012804
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![outpu2](https://github.com/KUSHALI104/Circulate-the-values-of-N-variables/assets/150231135/5615881b-ef67-440c-add4-81bc116c42dd)

## Result:
The program has excuted successfully.
