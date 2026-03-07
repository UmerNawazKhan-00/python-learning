# ==============================
# Python User Input
# ==============================

# The input() function allows a user to enter data.
# IMPORTANT: input() always returns a STRING.

# --------------------------------
# 1. Basic Input Example
# --------------------------------

name = input("Enter your name: ")
print("Welcome", name)


# --------------------------------
# 2. Input With Type Check
# --------------------------------

age = input("Enter your age: ")
print("Your age is:", age)

# Check the data type
print("Data type of age:", type(age))


# --------------------------------
# 3. Multiple Inputs (No Type Casting)
# --------------------------------

name = input("Enter your name: ")
age = input("Enter your age: ")
marks = input("Enter your marks: ")

print("Welcome", name)
print("Age =", age)
print("Marks =", marks)


# --------------------------------
# 4. Input With Type Casting
# --------------------------------

# Type casting converts a value from one data type to another.

name = str(input("Enter your name: "))
age = int(input("Enter your age: "))
marks = float(input("Enter your marks: "))

print("Welcome", name)
print("Age =", age)
print("Marks =", marks)
