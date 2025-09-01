# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a python program to perform addition and division operation using class and if,elif..

note:

class name should be saveetha, function name should be setvalues( to set a and b values) add and div

cases : choice 1 ->perform addition ,choice 2-> perform division ,  choice 0 -> exiting, other choices -> print 'invalid choice'

---

### ALGORITHM

1. Begin the program.  
2. Create a class `Saveetha`.  
3. Define the following methods inside the `Saveetha` class:  
   - `__init__(self)`: Initializes `a` and `b` to zero.  
   - `setvalues(self, a, b)`: Sets the values of `a` and `b`.  
   - `add(self)`: Performs the addition operation.  
   - `div(self)`: Performs the division operation. If `b` is zero, returns an error message for division by zero.  
4. Create a `main()` function.  
5. Take input from the user for the values of `a` and `b` using `setvalues(a, b)` method.  
6. Use a `while True` loop to repeatedly ask the user for a choice:  
   - If the choice is 1, call the `add()` method and print the result.  
   - If the choice is 2, call the `div()` method and print the result. Handle division by zero.  
   - If the choice is 0, print "Exiting!" and exit the loop.  
   - If the choice is not 1, 2, or 0, print "Invalid choice".  
7. Terminate the program.

---

### PROGRAM

```
class saveetha:
    def setvalues(self):
        self.a = int(input())
        self.b = int(input())

    def add(self):
        result = self.a + self.b
        print("Result: ", result)

    def div(self):
        if self.b != 0:
            result = self.a // self.b
            print("Result: ", result)
        else:
            print("Division by zero is not allowed.")

# Create object
obj = saveetha()
obj.setvalues()

while True:
    choice = int(input())
    if choice == 1:
        obj.add()
    elif choice == 2:
        obj.div()
    elif choice == 0:
        print("Exiting!")
        break
    else:
        print("Invalid choice")


```

### OUTPUT
<img width="452" height="343" alt="image" src="https://github.com/user-attachments/assets/dea4a231-41c5-4cb1-bb14-ecfd28321208" />

### RESULT
Thus a python program to perform addition and division operation using class and if,elif.. has been executed successfully.
