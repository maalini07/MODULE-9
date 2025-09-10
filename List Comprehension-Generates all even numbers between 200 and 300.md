# 🧾 List Comprehension:Generates all even numbers between 200 and 300
## 🎯 AIM:
To write a Python class-based program that generates all even numbers between 200 and 300 using **list comprehension**, and stores them in a list.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a class named `program`
3. Create variables `a`, `b`, and `c` to represent:
   - `a`: Lower limit
   - `b`: Step value
   - `c`: Upper limit
4. Initialize the values using a constructor `__init__`
5. Define a method `display()` that uses **list comprehension** to store even numbers
6. Print the resulting list of even numbers
7. **Stop**

---

## 💻 PROGRAM:
```
def __init__(self, start, end):
    self.start = start
    self.end = end
    self.even_numbers = self._generate_even_numbers()
def _generate_even_numbers(self):
    return [num for num in range(self.start, self.end + 1) if num % 2 == 0]
def get_even_numbers(self):
    return self.even_numbers
```

## OUTPUT:
<img width="814" height="201" alt="445723396-386e8e80-d4fc-49a8-838e-9f55a90ce7f0" src="https://github.com/user-attachments/assets/b55c771c-ee54-4c2e-b58c-1d0c9ab1edf2" />

## RESULT:
Thus, the program has executed successfully
