# Exp.No:16  
## DICTIONARY - MINIMUM AND MAXIMUM VALUE OF DICTIONARY

### AIM  
To write a Python program to find the **maximum** and **minimum** values from a dictionary.

### ALGORITHM

1. Start the program.  
2. Create a dictionary with key-value pairs.  
3. Extract all values using the `.values()` method.  
4. Use the `max()` function to find the maximum value.  
5. Use the `min()` function to find the minimum value.  
6. Print both maximum and minimum values.  
7. End the program.

### PROGRAM

```
dict1 = {'key 1': 200, 'key 2': 300}

# Extracting values from the dictionary
values = dict1.values()

# Finding maximum and minimum values
max_value = max(values)
min_value = min(values)

# Printing the results
print(f"{max_value} is maximum")
print(f"{min_value} is minimum")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/144597af-877e-415e-8d07-001ad6012db3)

### RESULT
Thus the program was successfully executed and the maximum and minimum values from the dictionary were displayed correctly.
