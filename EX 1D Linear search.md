# EX 1D Linear search
## DATE:
## AIM:
To write a python program for a search function with parameter list name and the value to be searched using string values.



## Algorithm
1. Read an integer l and then take l string inputs into a list List.
2. Read the target string n to be searched.
3. Initialize a variable found as False.
4. Iterate through each element in List and compare with n. If a match is found, set found = True and break.
5. Print "Found" if found is True; otherwise, print "Not Found".
## Program:
```
Program to implement a search function with parameter list name and the value to be searched using string values.
Developed by: LOKNAATH P 
Register Number: 212223240080
```
```python
def search(List,n):
    if n in List:
        return "Found"
    return "Not Found"
    
length=int(input())
List=[input() for _ in range(length)]
n=input()
print(search(List,n))
```

## Output:
![image](https://github.com/user-attachments/assets/460b44fe-d941-43b9-9c56-7c63bea03b43)



## Result:
The program was executed successfully, and it correctly checks if the input element is present in the list, printing "Found" if the element exists or "Not Found" if it does not.
