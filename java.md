- [Basics](#basics)
    - [Basic Boilerplate Code - Hello World Program](#basic-boilerplate-code---hello-world-program)
    - [User Input](#user-input)
    - [Data Types](#data-types)
      - [Primitive Data Type](#primitive-data-type)

## Basics

#### Basic Boilerplate Code - Hello World Program
```java
public class test{

    public static void main(String[] a){
        System.out.println("Hello World");
    }
}

```

#### User Input

To take user input, first we will import Scanner class.

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

#### Data Types

##### Primitive Data Type

|Data Type   | Example  | Size |
|---|---|
| **Byte**|byte a = 100;| 1 byte|
|**Short**|short a = 500;| 2 byte|
| **Integer**  | int a = 5;  |

