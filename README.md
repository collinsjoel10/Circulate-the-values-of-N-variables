# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
enter the function def
### Step 2: 
enter the eval input
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
enter the l value
### Step 6: 
print the program
## Program:
```
#Program to circulate N values.
#Developed by: 
#RegisterNumber:
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## OUTPUT:
![output](circulate.png)

## RESULT:
Thus the program is successfully executed.