# Matrix Operations-Diagonal Matrix Elements Printer 🧮

This Python program reads a matrix of any size from the user and prints **only the diagonal elements**, leaving other elements blank in the output.

## 📌 Aim

To write a Python program that prints only the diagonal elements of a given matrix.

## 🧠 Algorithm

1. Read the number of rows and columns from the user.
2. Initialize an empty matrix of size `rows × columns`.
3. Populate the matrix with user input.
4. Display the full matrix.
5. Iterate through the matrix and:
   - If `i == j`, print the element (main diagonal).
   - Else, print a blank space.
6. Print a newline after each row.

## 🖥️ Program
```
  rows=int(input())
  columns=int(input())
  matrix=[[0]*columns for row in range(rows)]
  for i in range(rows):
      lines = list(map(int,input().split()))
      for j in range(columns):
          matrix[i][j]=lines[j]
  print(matrix)
  for i in range(rows):
      for j in range(columns):
          if(i==j):
              print(matrix[i][j],end=' ')
          else:
              print(" ",end=' ')        
      print()
```

### Output:
<img width="760" height="289" alt="444372998-d39019f6-0de3-4fc7-81d9-975a8ee03372" src="https://github.com/user-attachments/assets/c49340fe-0638-461f-805d-c390ccc362bd" />

## Result
Thus, the program has executed successfully
