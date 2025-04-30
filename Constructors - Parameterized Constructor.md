# Exp.No:21  
## Constructors - Parameterized Constructor

---

### AIM  
To write a Python code to create a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the `userid` of the person.

---

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `userid` to `self.userid`.  
5. Print the `self.userid`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `s1` of the `person` class by passing the entered `name` and `userid` to the constructor.  
8. Terminate the program.

---

### PROGRAM

```
class person:
    def __init__(self,name,id):
        self.name=name
        self.id=id
    def display(self):
        print(id)
name=input()
id=input()
obj=person(name,id)
obj.display()

```

### OUTPUT
![image](https://github.com/user-attachments/assets/a119d1a3-a61e-47f6-8b2f-47bed957f670)


### RESULT
Thus the Python code for creating a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the `userid` of the person is successfully done.
