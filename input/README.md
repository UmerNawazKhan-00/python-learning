# =====================================
# Python User Input
# =====================================
# Demonstrates:
# - Basic input()
# - Checking data types
# - Multiple inputs
# - Type casting (str, int, float)

# -------------------------------------
# 1. Basic Input Example
# -------------------------------------

name = input("Enter your name: ")
print("Welcome", name)


# -------------------------------------
# 2. Input With Type Check
# -------------------------------------

age = input("Enter your age: ")

print("Your age is:", age)
print("Data type of age:", type(age))


# -------------------------------------
# 3. Multiple Inputs (Without Type Casting)
# -------------------------------------

name = input("Enter your name: ")
age = input("Enter your age: ")
marks = input("Enter your marks: ")

print("Welcome", name)
print("Age =", age)
print("Marks =", marks)


# -------------------------------------
# 4. Input With Type Casting
# -------------------------------------

name = str(input("Enter your name: "))
age = int(input("Enter your age: "))
marks = float(input("Enter your marks: "))

print("Welcome", name)
print("Age =", age)
print("Marks =", marks)

```python
your code
```
