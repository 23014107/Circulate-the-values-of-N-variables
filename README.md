# Circulate-the-values-of-N-variables
NAME: RAMYA.P
REG NO: 212223240137
DEPT:AIML

## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2:
Initialize the values in the list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Slice the number of values required
### Step 6:
Then paste it at the back to circulate
## Program:
```
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![Screenshot 2024-04-12 091853](https://github.com/23014107/Circulate-the-values-of-N-variables/assets/151625620/c514193e-8c5b-484b-9b76-48b86de9567b)

## Result:
Thus the circulate values of n variable output was verified successfully
