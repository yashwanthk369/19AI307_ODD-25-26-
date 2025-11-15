# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:

Write a Java program to reverse a number using a while loop. For example, if the input is 1234, the output should be 4321

## AIM:
To reverse a given integer using a while loop in Java.

## ALGORITHM :

1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the input number from the user.
4.	Set rev = 0.
5.	Use a while loop: extract last digit using num % 10, build reverse using rev = rev * 10 + digit, update num = num / 10.
6.	Print the reversed number.
7.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: Yashwanth K
RegisterNumber: 212224040369 
*/
```

## SOURCE CODE:
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int number = scan.nextInt();
        int ReverseNumber = 0;
        while(number > 0) {
            int digit = number % 10;
            ReverseNumber = (ReverseNumber * 10) + digit;
            number = number / 10;
        }
        System.out.println("Reversed number: "+ReverseNumber);
    }
}
```

## OUTPUT:

<img width="527" height="205" alt="Screenshot 2025-11-14 135656" src="https://github.com/user-attachments/assets/ede84122-4b48-48c7-b29e-9c5a711d2e72" />

## RESULT:

Thus the output is executed successfully.








