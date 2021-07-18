# C Cheatsheet

## Table of content

1. [Basics](#Basics)
2. []()

---

## Basics

<br>

### Boilerplate Code

```c
#include<stdio.h>
int main(){
    return 0;
}
```
### printf() function
It is used to print anything/show output on console

```c
printf("Hello World");
```
### scanf() function
It is used to take input from user

```c
scanf("format specifier",variable_name);
```
### Variables 
It is data name that is used to store the data value in the memory.

Rules to declare variables:

Variable Name | Valid? | Why? |
---|---|---|
int | Not Valid | keywords are not allowed |
amount$ | Not Valid | Dollar Sign is not allowed |
your name | Not Valid | Space between variable name is not allowed |
average_score | Valid | underscore can be used as space |
First_name | Valid | - |
int_type | Valid | Keywords can be used as combination |

<br>

### Basic Data Types

**char** - It stores single character. Size - 1 byte
```c
char var_name = 'a';
// Another example
char var_name2 = 'x';
```

**int** - It stores an integer value. Size - 4 bytes

```c
int age = 18;
//Another example
int amount = 10000;
```

**float** - It stores an floating point value with 6 digit precision. Size - 4 bytes

```c
float radius = 5.8;
//Another example
float area = 15.2;
```

**double** - It stores an float value with 14 digit precision. Size - 8 bytes.

```c
double var = 12.1531452;
//Another Example
double more_var = 542.12452;
```

**void** - Represents the absense of type.

```c
void main(){
    //does not return anything.
}
```

### Operators

**Arithmetic Operators**

|   |   |
|---|---|
|   |   |
