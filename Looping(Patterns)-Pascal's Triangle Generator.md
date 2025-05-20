# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---
## NAME :  M ALMAAS JAHAAN
## REG NO: 212224230016
## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
def triangle(n):
    for i in range(n):
        num=1
        row=[]
        for j in range(i+1):
            row.append(num)
            num=num*(i-j)//(j+1)
        print(*row)
n=int(input())
triangle(n)
```

## Sample Output
![image](https://github.com/user-attachments/assets/6ee31f73-6e41-4c0d-8e1e-0a6421832843)

## Result
Thus,the program is executed successfully.
