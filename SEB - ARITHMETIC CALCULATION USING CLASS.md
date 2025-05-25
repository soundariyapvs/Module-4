# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

### AIM  
To write a Python program that uses a class to perform **modulo** and **integer division** operations, allowing the user to select which operation to perform through a menu-driven loop.

### ALGORITHM

1. Define a class `SEC` with methods `setvalues(a, b)`, `modulo()`, and `division()`.
2. Accept two integer inputs for `a` and `b`.
3. Create an object of the `SEC` class and set the values using `setvalues()`.
4. Create a loop that allows the user to choose between the modulo and division operations.
5. Exit the loop when the user selects `0`.

### PROGRAM

```
class SEC:
    def setvalues(self, a, b):
        self.a = a
        self.b = b

    def modulo(self):
        return self.a % self.b

    def division(self):
        return self.a // self.b

a = int(input())
b = int(input())
r = SEC()
r.setvalues(a, b)

while True:
    choice = int(input("Enter 1 for Modulo, 2 for Division, 0 to Exit: "))
    if choice == 1:
        print(f"Result:  {r.modulo()}")
    elif choice == 2:
        print(f"Result:  {r.division()}")
    elif choice == 0:
        print('Exiting!')
        break
    else:
        print('Invalid input')
```

### OUTPUT
![image](https://github.com/user-attachments/assets/daa5b027-6744-448f-8351-8346bea7110f)

### RESULT
Thus the program was successfully executed, performing modulo and integer division operations as per user input, and handling invalid choices properly through a menu-driven interface.
