# Python User Input

The `input()` function allows a user to enter data in a Python program.

⚠️ **Important:**  
`input()` always returns data as a **string**.

---

## 1. Basic Input Example

```python
name = input("Enter your name: ")
print("Welcome", name)
```

---

## 2. Input With Type Check

```python
age = input("Enter your age: ")

print("Your age is:", age)
print("Data type of age:", type(age))
```

---

## 3. Multiple Inputs (Without Type Casting)

```python
name = input("Enter your name: ")
age = input("Enter your age: ")
marks = input("Enter your marks: ")

print("Welcome", name)
print("Age =", age)
print("Marks =", marks)
```

---

## 4. Input With Type Casting

Type casting converts a value from one data type to another.

```python
name = str(input("Enter your name: "))
age = int(input("Enter your age: "))
marks = float(input("Enter your marks: "))

print("Welcome", name)
print("Age =", age)
print("Marks =", marks)
```
