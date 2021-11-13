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
    - [Logical Operators](#logical-operators)
    - [Relational Operators](#relational-operators)
    - [Bitwise Operator](#bitwise-operator)
- [Conditional Statements](#conditional-statements)
  - [If Statements](#if-statements)
  - [Else Statement](#else-statement)
  - [Else if Statements](#else-if-statements)
- [Switch Statement](#switch-statement)
- [Loops](#loops)
  - [While Loop](#while-loop)
  - [For Loop](#for-loop)
  - [Do While Loop](#do-while-loop)
- [Break/Continue Statements](#breakcontinue-statements)
- [Arrays](#arrays)
  - [Declaring Array](#declaring-array)
  - [Defining Array](#defining-array)
  - [Access an Array Element](#access-an-array-element)
  - [Array Length](#array-length)
- [2D Array](#2d-array)
- [Methods (Functions)](#methods-functions)
  - [Declaring Method](#declaring-method)
    - [Method Overloading](#method-overloading)
- [Recursion](#recursion)

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
- Logical Operators
- Relational Operators
- Bitwise Operators
  
#### Arithmetic Operators

| Operator | Name           | About                            | Example |
| -------- | -------------- | -------------------------------- | ------- |
| +        | Addition       | Adds the variables               | a + b   |
| -        | Subtraction    | Subtracts the variables          | a - b   |
| *        | Multiplication | Multiply the variables           | a * b   |
| /        | Division       | Divides the variables            | a / b   |
| %        | Modulus        | prints the remainder of division | a % b   |
| ++       | Increment      | Increment the values by 1        | a++     |
| --       | Decrement      | Decrement the values by 1        | a--     |

#### Logical Operators

| Operator  | Name  |About|Example|
|---|---|---|---|
| &&   | Logical AND  | If any one of the condition is false, then result becomes false.|A && B (If A is true and B is false then result is FALSE)|
| \|\| |Logical OR| If any one of the condition is true then result becomes true| A \|\| B (If A is true and B is false then result is TRUE)|
|!|Logical NOT| It is used to reverse the logical state of operand. If condition is FALSE then NOT operator will make it TRUE| !A (Here If A is TRUE the !A(NOT A) becomes FALSE)|

#### Relational Operators
| Operator  | Name  |About|Example|
|---|---|--|--|
| ==  | Equals to  |Check two variables if they are equal or not| a == b|
| <|Less than| Checks if left variable is less than or not of right variable| a < b|
|>|Greater than| Checks if left variable is greater than or not of right variable| a > b|
|<=| Less than or equal to| Check if left variable is less than or equal to right variable| a <= b|
|>=|Greater than or equal to| Checks if left variable is greater than or equal to right variable| a>=b|

#### Bitwise Operator

*In progress*


## Conditional Statements

### If Statements
`if` statements are used to specify block of code to be executed if condition is `true`

```java
if(condition){
    //block of code
}

//EXAMPLE:
int a = 5;
int b = 2;
if(a > b){
  System.out.println("A is greater");
}
```

### Else Statement 

`else` block is executed if the `if` block is `false`

```java
if(condition){
  //code
}
else{
  //executed this block if above "if" block is false
}
```

### Else if Statements
`else if` is used to specify multiple if condition.

```java
if(condition){
  //code 1
}
else if(condition2){
  // execute this block if above "if" is false.
}
else if(condition3){
  // execute this block if above "else if" block is false.
}
else{
  // execute this if all above block is false.
}
```

## Switch Statement

```java
switch(condition){
  case A:
    // code
    break;

  case B:
    //code
    break;
  
  case C:
    //code
    break;
  
  default:
    //code
}
```

## Loops

### While Loop
```java
while(condition){
  //code
}
```
Example Code:

```java
//print 1 to 10
int i=1;
while(i<=10){
  System.out.println(i);
  i++;
}
```

### For Loop
```java
for(initialization; condition; increment/decrement){
  //code
}

//print 1 to 10

for(int i=1; i<=10; i++){
  System.out.println(i);
}
```

### Do While Loop
```java
do{
  //loop body or code
}
while(condition);


//Example Code:
int i=1;
do{
  System.out.println(i);
  i++;
}
while(i<=10);
```

## Break/Continue Statements

`break` statement is used to jump out of the loop.

```java
for(int i=1; i<=10;i++){
  //break loop if value of i becomes 5
  if(i == 5){
    break;
  }
  System.out.print(i + " ");
}

//OUTPUT:
// 1 2 3 4
```

`continue` statement is used skip the one iteration in the loop. 
```java
for(int i=1; i<=10; i++){
  if(i==5){
      continue;
  }
  System.out.print(i+" ");
}

// OUTPUT:
// 1 2 3 4 6 7 8 9 10
// Here 5 is skipped
```

## Arrays
Arrays are used to store multiple values of same data type in single variable. Array Index starts from 0.

### Declaring Array
```java
int[] id; //declaring array
id = new int[5]; //allotting memory to array

//Another Way to declare array
int[] id = new int[5];
```
### Defining Array
```java
int[] id = {1,2,3,4,5};
```

### Access an Array Element
```java
String[] arr = {'ABC','XYZ', 'PQR'};
System.out.println(arr[1]);

//Changing Array Element
arr[2] = "RST";
//"PQR" will be changed to "RST"
```
### Array Length
```java
System.out.println(arr.length);
```

## 2D Array
```java
//Creating 2x2 Matrix Array
int[2][2] matrix = new int[2][2];
//the two brackets( [2][2] ) represents no. of rows and columns
// Here array of 2 row and 2 col are declared.

//defining array
int[2][2] matrix = {
// COL 1  COL 2
  {12,    54},   // ROW 1
  {67,    23}    // ROW 2 
};
```

## Methods (Functions)

### Declaring Method
```java
//SYNTAX
returnType methodName(parameters){
  //code
}

//EXAMPLE
int printNum(int a){
  return a;
}

//CALLING METHOD
//SYNTAX : methodName(arguments);
// EXAMPLE:
    printNum(5);
//     ↑     ↑
//  Method   Arguments
//  Name
```

#### Method Overloading

Two or more methods can have same name but different parameters, such methods are called "overloaded methods".

```java
//Method 1 (0 Arguments)

static void greet(){
  System.out.println("Good Morning");
}

//Method 2 (1 Arguments)
static void greet(String name){
  System.out.println("Good Morning " + name);
}

//Calling Both Methods
greet();                //OUTPUT: Good Morning
greet("Carl Johnson")   //OUTPUT: Good Morning Carl Johnson
```

## Recursion
Recursion is the technique of making a function call itself.

```java
//Factorial of Number in Recursion
static int factorial(int n){
  if(n == 0){
    return 1;
  }
  return n * factorial(n-1);
//                ↑
//          This is recursive function call.
}
```

##