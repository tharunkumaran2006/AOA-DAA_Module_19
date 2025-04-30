# EX 1A Reverse a String
## DATE:
## AIM:
To write a program to create a recursive function to reverse a string.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
Program to implement Reverse a String
Developed by: LOKNAATH P
Register Number: 212223240080
```
```python

def reverse_string(s):
    if len(s) == 0:  
        return s
    else:
        return s[-1] + reverse_string(s[:-1]) 

input_string = input()
reversed_string = reverse_string(input_string)
print(reversed_string)
```

## Output:
![image](https://github.com/user-attachments/assets/05c7cd04-9766-4b86-9c3f-a12b95331e48)


## Result:
The program successfully reverses the input string using recursion. When the user provides an input string, the output displays the reversed version of the string
