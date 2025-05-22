# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```python
class Rectangle():
    def __init__(self,a,b):
        self.a=a
        self.b=b
    def display_private(self):
        print(self.a)
        print(self.b)
rect1=Rectangle(5,3)
rect1.display_private()
```

## Output

![image](https://github.com/user-attachments/assets/4fd00f82-71f7-4811-9e7c-937148dc1341)


## Result

Thus, the program is executed successfully.
