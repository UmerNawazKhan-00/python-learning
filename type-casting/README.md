# Type Casting in Python

## What is Type Casting?

Type casting is the process of converting a value from one data type to another.

Python provides built-in functions to convert data types when needed.

---

## Types of Type Casting

### Implicit Type Casting

Implicit casting happens automatically when Python converts a smaller data type to a larger data type.

Example:

```python
a = 5      # int
b = 2.5    # float

result = a + b
print(result)
print(type(result))
```

Output:

```
7.5
<class 'float'>
```

Python automatically converts `a` from **int → float**.

---

### Explicit Type Casting

Explicit casting happens when the programmer manually converts one data type into another.

Example:

```python
age = "18"

age = int(age)
print(age)
print(type(age))
```

Output:

```
18
<class 'int'>
```

---

## Common Type Casting Functions

| Function | Converts To | Example |
|--------|-------------|---------|
| int() | Integer | `int("10")` |
| float() | Float | `float("3.5")` |
| str() | String | `str(100)` |
| bool() | Boolean | `bool(1)` |

Example:

```python
num = "25"

number = int(num)
print(number)

price = 10
text = str(price)
print(text)
```
