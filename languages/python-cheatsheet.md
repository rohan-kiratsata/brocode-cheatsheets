
# Python Cheatsheet

**Table of Content**
- [Python Cheatsheet](#python-cheatsheet)
  - [Basics](#basics)
    - [Arithmetic Operations](#arithmetic-operations)
    - [Basic Data Types](#basic-data-types)
    - [Taking User Input](#taking-user-input)
  - [Strings](#strings)
    - [Creating String](#creating-string)
    - [String Concatenation](#string-concatenation)
    - [String Replication](#string-replication)
  - [Lists](#lists)
    - [Combine Two List](#combine-two-list)
    - [Nested List](#nested-list)
    - [Sorting List](#sorting-list)
    - [Copy a List](#copy-a-list)
  - [Tuples](#tuples)
    - [Convert Tuple to List](#convert-tuple-to-list)
  - [Sets](#sets)
    - [Creating a Set](#creating-a-set)
    - [Set Operations](#set-operations)
  - [Dictionaries](#dictionaries)
    - [Creating Dictionaries](#creating-dictionaries)
    - [Dictionary Operations](#dictionary-operations)
  - [Conditional Statements](#conditional-statements)
    - [If Statement](#if-statement)
    - [Elif Statement](#elif-statement)
    - [Else Statement](#else-statement)
  - [Loops](#loops)
    - [While Loops](#while-loops)
    - [For Loop](#for-loop)
  - [Functions](#functions)
    - [Creating a Function](#creating-a-function)
    - [Calling Function](#calling-function)
    - [Passing Arguments](#passing-arguments)
  - [Lambda Functions](#lambda-functions)


## Basics

### Arithmetic Operations
```python
>>> 5 + 2   # Addition
7
```
```python
>>> 4 - 3   # Subtraction
1
```
```python
>>> 4 * 4   # Multiplication
16
```
```python
>>> 10 / 2  # Division
5.0         # Return float value

>>> 10 // 2 # Division, but return integer value
5
```
```python
>>> 10 % 2 # Modulas(Remainder)
0
```
```python
>>> 2 ** 3 # Exponenet(Power)
8
```

### Basic Data Types

| Data Type | Example                    |
| --------- | -------------------------- |
| Integer   | `-2,-1,0,1,2`              |
| Float     | `-1.5, -1.92, 2.25, 16.4`  |
| String    | `'python'`,`'is'`,`'love'` |
| Complex   | `1j`, `1+2j`               |
| Boolean   | `x = True`, `x = False`    |

### Taking User Input
input() function is used to take input from the user.

```python
name = input("Enter Your Name:")
print("Hello " + name)
```

## Strings

### Creating String

```python
 myString = "Python is easy!"
```

### String Concatenation

A way to add two string together using "+" operator.

```python
myString = "Python"
myString2 = "is easy"
ConString = myString + myString2
print(ConString)
```

Concatenating string and variable using , (comma).
```python
no_of_apples = 20
print("We have", no_of_apples,"apples in a basket")
# OUTPUT: We have 20 apples in a basket*
```

### String Replication

```python
string = "Python" * 5
print(string)
# OUTPUT: PythonPythonPythonPythonPython
```
## Lists
Lists are used to store the multiple items in a single variable. List are created using square brackets.
List elements are changeable, can allow duplicate elements, and has defined order and that order will not change.Any new element will be placed at end of list. List index will start from 0 and will end at n-1 (where n is number of elements).

**Creating List**
```python
lst = ["python","cpp","java"]
```
**Fetching Values from List**
```python
>>> lst = ["python","cpp","java"]
>>> lst[0]
"python"
>>> lst[1]
"cpp"
>>> lst[2]
"java"
```
**Adding Items to List**
```python
lst = [1,2,3]
lst.append(4)
print(lst)
# OUTPUT : [1, 2, 3, 4]
```
*Method 2*
insert() method is used to add item to specific index.
```python
lst = [1,3,4]
# SYNTAX : .insert(index number, element)
lst.insert(1,2)
print(lst)
# OUTPUT : [1,2,3,4]
```

**Removing Items from List**
```python
lst = [1,2,3,5]
lst.remove(5)
print(lst)
# OUTPUT : [1,2,3]
```

### Combine Two List
```python
lst1 = [1,2,3]
lst2 = ["x","y","z"]

combineList = lst1 + lst2
print(combineList)
# OUTPUT: [1, 2, 3, "x", "y", "z"]
```
### Nested List
```python
lst1 = [1,2,3]
lst2 = ["x","y","z"]
nestedList = [list1,list2]
print(nestedList)
# OUTPUT : [[1, 2, 3], ["x", "y", "z"]]
```
### Sorting List
```python
lst = [123,51,214,23,56]
lst.sort()
print(lst)
#OUTPUT : [23, 51, 56, 123, 214]
```
### Copy a List
```python
lst = ["a","b","c"]
lstcpy = lst.copy()
print(lstcpy)
# OUTPUT: ["a", "b", "c"]
```

## Tuples
Tuples are similar to list. However, they are immutable and you can't change the values stored in a tuple. Tuple are created using round brackets.

**Creating Tuple**
```python
myTuple = (1,2,3,4)
print(myTuple)
```

**Access Tuple Items**
You can access tuple items by referring to the index number.
```python
myTuple = (1,2,3,4)
print(myTuple[2])
# OUTPUT: 3
```

### Convert Tuple to List
Since Tuples are immutable. Instead we can convert tuple to list and can edit and then convert it back to tuple.

```python
myTuple = (1,2,3)
convertedTuple = list(myTuple)
# Now we can edit the "convertedTuple" list.
convertedTuple[0] = 120
# Converting back to Tuple.
myTuple = tuple(ConvertedTuple)
print(myTuple)
# OUTPUT: (120,2,3)
```

## Sets
Sets are used to store multiple items in a single variable.
A Set is a collection which is both unordered and unindexed.
Sets are written with curly brackets.
Set cannot have two items with same value.
A set can contain different data types.

### Creating a Set
```python
mySet = {"python", "java", "cpp"}
print(mySet)
```

### Set Operations

**Set with Different Data Types**
```python
mySet = {"python",142,True,"abc"}
```

**Adding Element to Set**
```python
mySet = {1,2,3}
s.add(4)
print(s)
# OUTPUT: {1,2,3,4}
```

**Adding Multiple Elements to Set**
```python
mySet = {1,2,3}
mySet.update([4,5,6,7])
print(mySet)
# OUTPUT : {1,2,3,4,5,6,7}
```

## Dictionaries
Dictionaries are used to store data in pairs.
A Pair contains **key** and **value**.
It is ordered,changeable and cannot contain duplicate values. If duplicate values found then it will overwrite the values.

### Creating Dictionaries
```python
# SYNTAX

# dictionary_name = {
# "key_name" : "Value",
# "key2_name" : "Value2"
# }

dict = {
    "name" : "Van Rossum",
    "ID" : 1234,
    "year" : 1956
}
```
### Dictionary Operations

**Printing Items**
```python
print(dict["name"])
```

**Length of Dictionary**
```python
print(len(dict))

# OUTPUT : 2
```
**Adding Items**
```python
dict = {
    "name" : "Van Rossum",
    "ID" : 1234,
    "year" : 1956
}
# Adding Item
dict["profession"] = "Programmer"
```
**Updating Item**
```python
# Syntax
# dict_name.update({"key":"value"})

dict.update({"ID":"9493"})
```

**Print All Items Values**
```py
for i in dict:
    print(dict[i])

# OUTPUT:
#   Van Rossum
#   9493
#   1956
```

## Conditional Statements

### If Statement
`If` statement contains a logical expressions using which data is compared and a decision is made.
```
if expression:
    statements or code

Note : Indentation is required in IF statement
```

```py
# Let's a create a program to check if person is eligible to vote or not

age = 15

if age < 18: # If age is less than 18 execute the block
    print("Not Eligible to Vote")

if age >= 18: # If age is greater than or equal to 18 execute the block
    print("Eligible to Vote")

# Here age is 15 so, 1st condition will be true and print the message.
```

### Elif Statement

`Elif` keyword used if the previous `if` condition is false then it will execute the `elif` condition.

```py
# Let's take the same example but using elif condition
age = 20

if age < 18:
    print("Not Eligible to Vote")

elif age >= 18:
    print("Eligible to Vote")

#OUTPUT: Eligible to Vote
```

### Else Statement

`else` keyword is used if all previous condition becomes false then it execute the `else` block.

```py
# Let us Understand using example of "If Number is +ve or -ve."

n = 0

if n > 0:
    print("N is +ve")

elif n < 0:
    print("N is -ve")

# In this case both the 'if' condition is false so we use 'else' block
else:
    print("N is Zero")

# OUTPUT: N is Zero
```

## Loops
Loops are used when we want to execute same thing repeatedly until condition is not satisfied. For example, If we want to print "Hello World" 100 times, we will write print statement 100 times. We will use loop to achieve this.

### While Loops

```py
# print hello World 100 times

i = 1 
while i <= 100:
    print("Hello World")
    i=i+1
```

### For Loop

```py
# Same example but using for loop

# for i in range(101)-> range function is used instead of "i<=100" from while loop
# Syntax for range() function -> range(n-1), So If n=100, range will only include 99.

for i in range(101):
    print("Hello World")

```
**Learn More about Range() Function [Here](https://www.geeksforgeeks.org/python-range-function/)**

## Functions

Functions are block of code which only runs when it is called. Functions are defined using `def` keyword. 

### Creating a Function

```
SYNTAX

def function_name():
    code inside function
```

```py
def my_function():
    print("Hello World")

```

### Calling Function

```py
def greeting():
    print("Good Morning")

# Calling Of Function
greeting()
```

### Passing Arguments

```py
# let us understand using example
# -> Take username and greet

# passing name argument
def greet(name):
    print("Hello " + name + ", Good Morning" )


greet("Rohan")

## Passing Two Arguments:

def greet(name, lastname):
    print("Hello " + name + lastname + ", Good Morning" )

greet("Rohan", "Kiratsata")
```

## Lambda Functions
A lambda function is a small anonymous function means function without name.

```
SYNTAX

lambda arguments: expression
```
```py
# Lambda function to square of number

n = lambda x : x*x

print(n(5))
```
