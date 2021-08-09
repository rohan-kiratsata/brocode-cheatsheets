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


## Basics

#### Arithmetic Operations
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

#### Basic Data Types

| Data Type | Example                    |
| --------- | -------------------------- |
| Integer   | `-2,-1,0,1,2`              |
| Float     | `-1.5, -1.92, 2.25, 16.4`  |
| String    | `'python'`,`'is'`,`'love'` |
| Complex   | `1j`, `1+2j`               |
| Boolean   | `x = True`, `x = False`    |

#### Taking User Input
input() function is used to take input from the user.

```python
name = input("Enter Your Name:")
print("Hello " + name)
```

## Strings

#### Creating String

```python
 myString = "Python is easy!"
```

#### String Concatenation

A way to add two string together using "+" operator.

```python
myString = "Python"
myString2 = "is easy"
ConString = myString + myString2
print(ConString)
```
#### String Replication

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

#### Combine Two List
```python
lst1 = [1,2,3]
lst2 = ["x","y","z"]

combineList = lst1 + lst2
print(combineList)
# OUTPUT: [1, 2, 3, "x", "y", "z"]
```
#### Nested List
```python
lst1 = [1,2,3]
lst2 = ["x","y","z"]
nestedList = [list1,list2]
print(nestedList)
# OUTPUT : [[1, 2, 3], ["x", "y", "z"]]
```
#### Sorting List
```python
lst = [123,51,214,23,56]
lst.sort()
print(lst)
#OUTPUT : [23, 51, 56, 123, 214]
```
#### Copy a List
```python
lst = ["a","b","c"]
lstcpy = lst.copy()
print(lstcpy)
# OUTPUT: ["a", "b", "c"]
```

## Tuples
Tuples are similar to list. Hovwever, they are immutable and you can't change the values stored in a tuple. Tuple are created using round brackets.

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

#### Convert Tuple to List
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

**Creating a Set**
```python
mySet = {"python", "java", "cpp"}
print(mySet)
```

**Set with Differnt Data Types**
```python
mySet = {"python",142,True,"abc"}
```
