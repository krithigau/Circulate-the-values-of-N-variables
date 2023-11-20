# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a function named circulate.
### Step 2: 
Get the value from the user for the list creation.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Getting the length of the list in l variable.
### Step 5: 
Write appropriate if condition.
### Step 6: 
In print function using the slicing concept rotate the list as and give appropriate output.
## Program:
```
#Program to circulate N values.
#Developed by: U KRITHIGA
#RegisterNumber:23006499
def circulate():
    L=eval(input())
    n=int(input())
    l=len(L)
    if n<=len(L):
       print('After circulating the values are:',L[n:]+L[:n])
```

## Output:
![Alt text](<circulate ss.png>)

## Result:
Circulate the n variables using function concept is made successful!
