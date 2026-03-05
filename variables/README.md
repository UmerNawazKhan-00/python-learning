# Variables in Python

## What is a Variable?

A **variable** is a named container used to store data in a program so it can be used later.

You can think of a variable like a **labeled box**:

* **Variable name** → the label on the box
* **Value** → the data stored inside the box

Instead of repeating values throughout your code, you store them in variables and reuse them.

---

## Basic Example

```python
age = 18
name = "Omer"
height = 5.9
```

In this example:

* `age` stores the number **18**
* `name` stores the text **"Omer"**
* `height` stores the number **5.9**

---

## Using Variables

Variables can be used anywhere in the program after they are created.

```python
age = 18
print(age)
```

**Output**

```
18
```

Python looks at the variable `age` and prints the value stored in it.

---

## Why Variables Are Important

Without variables, you would repeat values many times.

**Without variables**

```python
print(18 + 2)
print(18 + 5)
```

**With variables**

```python
age = 18
print(age + 2)
print(age + 5)
```

If the value changes, you only update it **once**.

---

## Variable Naming Rules

Valid variable names:

```python
age
user_name
score1
```

Invalid variable names:

```python
1age
user-name
class
```

**Rules**

* Cannot start with a number
* Cannot contain spaces
* Cannot use special characters like `-`
* Cannot use Python keywords

---

## Data Types Variables Can Store

Variables can store different types of data.

| Type    | Example          |
| ------- | ---------------- |
| Integer | `10`, `25`, `-3` |
| Float   | `3.14`, `5.9`    |
| String  | `"hello"`        |
| Boolean | `True`, `False`  |

Example:

```python
price = 10        # integer
pi = 3.14         # float
name = "Omer"     # string
is_student = True # boolean
```

---

## Practical Example

```python
price = 50
discount = 10

final_price = price - discount
print(final_price)
```

**Output**

```
40
```

---

## Key Takeaway

Variables allow programmers to **store, reuse, and manipulate data efficiently**, making programs easier to write and maintain.
