# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:

Write a java program to get name from the user (String) and print it.

## AIM:

To write a Java program that accepts a String value (a person's name) as input from the user and then displays the received name back to the console.

## ALGORITHM :
1.	Start: Begin the Java program and load the Scanner tool.
2. Prompt: Ask the user to type their name in the console.
3. Read: Use the Scanner to capture the complete String the user enters.
4. Print: Display the captured name back to the user with a welcoming message.
5. End: Close the Scanner resource and stop the program.



## PROGRAM:
 ```
/*
Program to implement variables and Operators using Java
Developed by: Yashwanth K
RegisterNumber: 212224040369
*/
```

## Sourcecode.java:

```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        String a = scan.nextLine();
        System.out.print("Hello, "+a);
    }
}
```
## OUTPUT:

<img width="503" height="133" alt="image" src="https://github.com/user-attachments/assets/13738a14-1add-47fb-85fa-ade4e7f378ef" />

## RESULT:

Thus the output is executed successfully.

