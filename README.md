# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the two values from the user
### Step 2: 
In circular swapping, the value of the first variable is assigned to the second variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be circulated
### Step 6: 
End the program
## Program:
# Program to circulate N values.
# Developed by: VIKAASH K S
# RegisterNumber:23013426
def circulate():
    n=eval(input())
    a=int(input())
    n=n[a:]+n[:a]
    print("After circulating the values are:",n)
## Output:
![Screenshot 2023-10-27 214945](https://github.com/Vikaash19/Circulate-the-values-of-N-variables/assets/148514589/7a3d0a3c-6a54-4a8a-9591-9573d9fc36fa)
## Result:
Thus the Circulation of the values of N variables are successfully executed
