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
import math
rows=int(input())
for n in range(rows):
        print(" " * (rows - n), end=" ")
        for k in range(n + 1):
            # Compute C(n, k) = n! / (k! * (n-k)!)
            value = math.comb(n, k)
            print(value, end=" ")
        print()
```
## Sample Output
<img width="730" height="487" alt="image" src="https://github.com/user-attachments/assets/bd6fe062-6a8f-477e-bd5c-ec250c9b8453" />


## Result
Successfully wrote a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.
