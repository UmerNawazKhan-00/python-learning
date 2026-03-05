Data Types in Python
What Are Data Types?

A data type defines the kind of value a variable holds. Python automatically knows the type when you assign a value.

Data types are essential because they determine what operations you can perform on a variable.

Common Python Data Types
Type	Description	Example
int	Integer numbers (whole numbers)	10, -5, 0
float	Decimal numbers	3.14, 5.0
str	Text (string of characters)	"Hello", 'Python'
bool	Boolean values (True / False)	True, False
list	Ordered collection of values	[1, 2, 3], ["a", "b"]
tuple	Ordered, immutable collection	(1, 2, 3)
set	Unordered, unique collection	{1, 2, 3}
dict	Key-value pairs	{"name": "Omer", "age": 18}
Examples
# Integer
age = 18

# Float
height = 5.9

# String
name = "Omer"

# Boolean
is_student = True

# List
fruits = ["apple", "banana", "cherry"]

# Tuple
coordinates = (10, 20)

# Set
unique_numbers = {1, 2, 3}

# Dictionary
person = {"name": "Omer", "age": 18}
Checking the Data Type
age = 18
print(type(age))  # <class 'int'>

name = "Omer"
print(type(name))  # <class 'str'>
