# 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program

```python
class Beans(): 
    def type(self):
        print("Vegetable")
    def colour(self):
        print("Green")
class Mango(): 
    def type(self):
        print("Fruit")
    def colour(self):
        print("Yellow")
obj_beans = Beans() 
obj_mango = Mango() 
for given in (obj_beans,obj_mango):
    given.type()
    given.colour()
```

## Output

![image](https://github.com/user-attachments/assets/51d224dc-13d1-44de-a50c-539a26b082a5)


## Result

Thus, the program is executed successfully.
