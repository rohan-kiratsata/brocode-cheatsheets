## *In Progress...*

- [*In Progress...*](#in-progress)
- [Basics](#basics)
    - [Basic Boilerplate Code - Hello World Program](#basic-boilerplate-code---hello-world-program)
- [Comments](#comments)
  - [Single Line Comment](#single-line-comment)
  - [Multi-Line Comments](#multi-line-comments)
- [User Input in Java](#user-input-in-java)
- [Data Types](#data-types)
  - [Primitive Data Type](#primitive-data-type)
- [Java Operator](#java-operator)
  - [Types of Operators](#types-of-operators)
    - [Arithmetic Operators](#arithmetic-operators)

## Basics

#### Basic Boilerplate Code - Hello World Program
```java
public class test{

    public static void main(String[] a){
        System.out.println("Hello World");
    }
}

```
## Comments 
Comments are used to make code more readable or to explain java code. Comments are ignored while executing the code.
### Single Line Comment
Single Line comments starts with double forward slashes(//).
Syntax for Single Line Comment:

```java
//This is comment and will be ignored by java while executing.
System.out.println("HelloWorld");
```
### Multi-Line Comments
Multi-line comments starts with `/*` and ends with `*/`.
Any code between these two will be ignored.

```java
/*
This block will be ignored 
The code below will print hello world.
Example of multi-line comment
*/
System.out.println("HelloWorld");
```

## User Input in Java

To take user input, first we will import Scanner class. Learn more about Scanner class [here]()

```java

public class test{
    public static void main(String[] a){

        //Creating an object of scanner class.
        Scanner input = new Scanner(System.in);

        //Taking Integer Input from user 
        int testVar = input.nextInt();
    }
}
```


## Data Types

### Primitive Data Type

| Data Type     | Example              | Size    |
| ------------- | -------------------- | ------- |
| **Byte**      | byte a = 100;        | 1 bytes |
| **Short**     | short a = 500;       | 2 bytes |
| **Integer**   | int a = 5;           | 4 bytes |
| **Long**      | long a =1241351866L; | 8 bytes |
| **Float**     | float a = 15.87;     | 4 bytes |
| **Double**    | double a =2156.4674; | 8 bytes |
| **Boolean**   | bool isValid = true; | 1 bit   |
| **Character** | char letter = "J";   | 2 bytes |


## Java Operator

Operator are used to perform mathematical operations on variables and values.

### Types of Operators

- Arithmetic Operators
- Assignment Operators
- Logical Operators
- Comparison Operators
- Bitwise Operators
  
#### Arithmetic Operators

|Operator  |  Name |About |Example|
|---|---|--|--|
| +  | Addition  |Adds the variables| a + b|
|-|Subtraction|Subtracts the variables|a - b|
|*|Multiplication|Multiply the variables| a * b|
|/| Division|Divides the variables|a / b|
|%| Modulas| prints the remainder of division|a % b|
|++| Increment| Increment the values by 1| a++|
|--|Decrement| Decrement the values by 1|a--|
