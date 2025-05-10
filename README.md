# Python_for_Testers

## Lesson 4: Variables
📘 Lesson Summary:
In Python, variables are labels for data — whether it's numbers (integers) or text (strings). Good code starts with clear labels, tested outputs, and an understanding of how each piece fits together.

### 🧪 Python Variable Testing – Code 
x = 10
Institute = "Testing Funda"

print(x)
print(Institute)

print("Testing Funda 1")

### 💡 Purpose of the Code
This simple Python script demonstrates the use of variables, data types, and basic output testing. It serves as a foundational example for understanding how Python handles and prints different types of data — integers and strings.

### 📦 Key Concepts Demonstrated
Variable Declaration:

x = 10 assigns an integer value.

Institute = "Testing Funda" assigns a string value.
This illustrates Python’s dynamic typing — no need to explicitly declare data types.

### Printing for Output Verification:

Using print() to confirm the values held in variables.

Also prints a static string to show direct output vs variable-based output.

### Readability & Naming:

Variables are named clearly, making the code easy to understand and maintain — a good practice for collaborative environments.

----------------------------------------------------------------------------------------------------

## Lesson 5: Variables Naming Rules
Summary: How does company format their text strings.

### Name should be descriptive and meaningful

total_price= 100;

### Variable name must start with a letter or an underscore

eggs = 5;
_eggs = 10;

### It should not be a number

 1eggs = 5;
 
### Variable name should contain Alphanumeric charachters and underscores (A-Z, a-z, 0-9, and _)

### Python is case sensitive

eggs = 5
EGGS = 5
Eggs = 5

### These will all return different variable associations

### Creating different variables which are allowed

mytraining = "python"
my_training = "python"
_mytraining ="python"
_my_training = "python"
myTraining = "python"
MyTraining = "python"
myTraining2 = "python"

### What is not allowed though

 my training = "python" 
 8myTraining = "python"

### Cases

### Pascal Case - Each word starts with a capital letter

MyEnrolledTraining = "python" 

### Snake Cse - Each word is seperated by an _ underscore

my_enrolled_training = "python"

### Camel Case - Each word except the first word starts with a capital letter

myEnrolledTraining = "python"

--------------------------------------------------------------------------

# Lesson 6: Data Types
--------------

# Numeric - interger 10, Float 10.5, Complex 50j

a = 10
b = 15.5
c = 50j

print(type(c))

# String - Testing Funda

d = """ This is Python for 
Automation testing

By Testing Funda"""

print(d)
print(type(d))

# Sequence: List, Tuple, Range
## list
list = [1,2,3,4,5]
print(list)
print(type(list))

## tuple
tuple = (1,2,3,4,5)

print(tuple)
print(type(tuple))

## range
range = range(1,6)

print(range)
print(type(range))

# Mapping of data {"name": "Sumaya"} - Dict

dict = {"name":"Testing Funda","Type":"Software testing Dataset"}

print(dict)
print(type(dict))

# Boolean Data Type = True or False
boolt = False

print(boolt)
print(type(boolt))

# Set Data Type

set = {1,2,3,4,5}
print(set)
print(type(set))

# Set & Frozensset
## Immutable & mutable
### Mutable can be modified and changed. Immutable cannot be changed or edited.

frozen = frozenset([1,2,3,4,5])
print(frozen)
print(type(frozen))


