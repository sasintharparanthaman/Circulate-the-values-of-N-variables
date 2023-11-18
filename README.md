# Circulate The values of N variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Start the program
### Step 2: 
Get the input from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Using the concatination operation display the entire rotated list
### Step 6: 
Stop the program
## Program:
```
#Program to circulate N values.
#Developed by: Sasinthar.P
#RegisterNumber:23012532
def circulate():
    list1=eval(input())
    n=eval(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![circulate](https://github.com/sasintharparanthaman/Circulate-the-values-of-N-variables/assets/145743219/e7ce0882-5f98-4800-9b2c-dbe7d9e4286b)

## Result:
The output is successful
