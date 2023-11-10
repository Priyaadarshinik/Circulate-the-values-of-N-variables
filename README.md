# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
The function is called which is in test case.
### Step 2: 
The function definition named circulate() is defined by the user.
### Step 3: 
Get the value from the user for the number of rotation.
### Step 4: 
Get the input for the list.
### Step 5:
Rotate the list using slicing concept. 
### Step 6: 
Using if condition print the circulated list.
## Program:
```
#Program to circulate N values.
#Developed by:PRIYAADARSHINI.K
#RegisterNumber:23000629
def circulate():
    L=eval(input())
    n=int(input())
    l=len(L)
    if n<=len(L):
        print("After circulating the values are:",L[n:]+L[:n])
```
## Output:
![output](/circulatedoutput.png)
## Result:
Thus the cirulation of the values of N variables is successfully executed.