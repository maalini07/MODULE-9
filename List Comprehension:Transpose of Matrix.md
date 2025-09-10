# 🧮 List Comprehension:Transpose of Matrix 

## 🎯 AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

## 💻 PROGRAM:
```
def create(r,c):
  M=[]
  for i in range(int(r)):
    R = []
  for j in range(int(c)):
    x = int(input())
  R.append(x)
  M.append(R)
  return M
r,c = input().split()
matrix =create(int(r),int(c))
print(matrix)

T = [[r[i]for r in matrix]for i in range(len(matrix[0]))]
print(T)
```
## OUTPUT:
<img width="773" height="496" alt="444372671-1aa8caea-0a48-4e23-9575-7b04e000b3b2" src="https://github.com/user-attachments/assets/855eaea4-1958-4914-8157-541c1bcbe2de" />

## RESULT:
Thus, the program has executed successfully
