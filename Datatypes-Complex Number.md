# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program

```


a = int(input())
b = int(input())

c = complex(a, b)

print("Complex Number =", c)
print("Real Part =", c.real)
print("Imaginary Part =", c.imag)

```



## Output

<img width="881" height="600" alt="image" src="https://github.com/user-attachments/assets/d42a4244-adf1-456a-b8ab-ab50178b81ac" />




## Result

The program reads two integers, creates a complex number using them, and displays the complex number along with its real and imaginary parts. This demonstrates the use of complex numbers in Python.
