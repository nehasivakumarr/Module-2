# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

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
n=int(input())
for i in range(n):
    print(" "*(n-i-1),end="")
    num=1
    for j in range(i+1):
        print(num,end=" ")
        num=num*(i-j)//(j+1)
    print()
```

## Sample Output
<img width="486" height="504" alt="{0F14380B-4C1F-4723-96B7-093ECD421386}" src="https://github.com/user-attachments/assets/92dc15bd-a293-40c7-ad77-68b72ef7f559" />


## Result
Thus, the python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

