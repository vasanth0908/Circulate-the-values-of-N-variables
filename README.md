# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Get the values from the user

### Step 2:
Assign the value of variable to a temporary variable

### Step 3:
Get the value from the user for the number of rotation

### Step 4:
Using the slicing concept rotate the list

### Step 5:
Print both the values it would be interchanged

### Step 6:
End the program
## Program:
```
#Program to circulate N values.
#Developed by: Vasanth.S
#RegisterNumber:212222110052
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```


## Output:
![10](https://github.com/vasanth0908/Circulate-the-values-of-N-variables/assets/122000018/2c438a27-eb11-47f5-a5a7-3ea06109040a)


## Result:
The output for circulate the values of n variables is successfull.
