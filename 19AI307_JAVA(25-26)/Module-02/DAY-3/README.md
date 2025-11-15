# Ex.No:2(C) ACCESS SPECIFIERS

## QUESTION:
Write a program to access a static variable using both class name and object.


## AIM:
To demonstrate accessing a static variable in Java using both the class name and an object.

## ALGORITHM :

1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Declare a class containing a static variable.
4. Access the static variable directly using the class name.
5.	Create an object of the class.
6.	Access the same static variable using the object.
7.	Display both outputs.
8.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Access Specifiers using Java
Developed by: Yashwanth K 
RegisterNumber: 212224040369
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

class Sample {
    static int number;

    Sample(int number) {
        Sample.number = number;
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int input = scan.nextInt();
        Sample obj = new Sample(input);
        System.out.println("Accessing using class name: " + Sample.number);
        System.out.println("Accessing using object: " + obj.number);
    }
}
```

## OUTPUT:

<img width="603" height="255" alt="image" src="https://github.com/user-attachments/assets/a40b7657-fde0-47b9-98e2-12ba7663330f" />

## RESULT:

Thus the output is executed successfully.

