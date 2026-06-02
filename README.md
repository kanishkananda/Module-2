## Name:N.Kanishka
## Register no:212225230127
# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a = 16
binary_representation = bin(a)
print(binary_representation)
```
## Output
<img width="1180" height="903" alt="image" src="https://github.com/user-attachments/assets/850271ce-9ced-4f72-a2c6-6ee07da70f4f" />

## Result
 Thus to write a Python program to convert the number 16 into its binary representation using built-in Python functions has been executed sucessfully.


 # Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a, b):
    print(a % b)

a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))
result(a, b)
```

## Output
<img width="1102" height="902" alt="image" src="https://github.com/user-attachments/assets/3372fe6d-8c6a-41b1-8a04-4a3d32284f24" />

## Result
 Thus To write a Python program that defines a function which accepts two values and returns their modulo using the % operator has been executed sucessfully.


 # Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))

f = lambda a, b: a + b
result = f(a, b)

print("Sum:", result)
```

## Output
<img width="1120" height="885" alt="image" src="https://github.com/user-attachments/assets/15f18ba0-41da-4311-b926-34144656ae29" />

## Result
 Thus To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum has been executed sucessfully.


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

rows = int(input("Enter the number of rows: "))

for n in range(rows):
    # Print leading spaces to shape the triangle
    print(' ' * (rows - n), end='')
    for k in range(n + 1):
        # Compute the binomial coefficient using factorials
        val = math.factorial(n) // (math.factorial(k) * math.factorial(n - k))
        print(val, end=' ')
    print()
```

## Sample Output
<img width="1089" height="900" alt="image" src="https://github.com/user-attachments/assets/57a819fa-f0ca-41f5-b4e4-0fdd01de926f" />

## Result
 Thus To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user has been executed sucessfully.


 ## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num = int(input("Enter a number: "))
temp = num
rev = 0

while temp > 0:
    rev = (10 * rev) + (temp % 10)
    temp = temp // 10

if rev == num:
    print(f"{num} is a palindrome.")
else:
    print(f"{num} is not a palindrome.")
```
## Output
<img width="1060" height="869" alt="image" src="https://github.com/user-attachments/assets/0b4dffd8-f96f-4ac4-a394-459390a99bf5" />


## Result
 Thus To write a Python program that checks whether a given number is a palindrome using loops has been executed sucessfully.
