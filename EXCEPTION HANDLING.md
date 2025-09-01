# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To Create a short program that prompts the user for a list of grades separated by commas. Split the string into individual grades and use a list comprehension to convert each string to an integer. You should use a try statement to inform the user when the values they entered cannot be converted.

---

### ALGORITHM
1. Begin the program.  
2. Read a string `user` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list `grades_str`.  
4. Use a `try` block to attempt converting each item in `grades_str` to an integer  
   and store the result in a list `grades`.  
5. If the conversion is successful, print the list `grades` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number),  
   catch the exception and print an error message:  
   "The grades you entered were in an invalid format." along with the original list `grades_str`.  
7. Terminate the program.  


---

### PROGRAM

```
Reg.No: 212223060188
Name: k.nithiyasree
Add Your Code Here

user=input()
grades_str=user.split(',')
try:
    grades=[int(g) for g in grades_str]
    print(grades)
except ValueError:
    print("The grades you entered were in an invalid format.")
    print(grades_str)
```

### OUTPUT:
<img width="1157" height="215" alt="image" src="https://github.com/user-attachments/assets/e085ba54-2baf-436c-8f20-942fb5f9adcd" />


### RESULT:
A short program that prompts the user for a list of grades separated by commas. Split the string into individual grades and use a list comprehension to convert each string to an integer has been executed successfully.
