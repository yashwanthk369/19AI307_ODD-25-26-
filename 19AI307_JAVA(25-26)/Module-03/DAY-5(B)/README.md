# Ex.No:3(F) WRAPPER CLASS

## QUESTION:
Write a Java program to reverse a number using the Integer wrapper class and compare it with the original number.

## AIM:
To operationalize Java’s Integer wrapper class for converting, reversing, and validating a number against its original form to determine palindrome status.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Accept the number from the user.
4.	Convert the integer into a String using the Integer wrapper class.
5.	Reverse the string using StringBuilder.
6.	Compare the original and reversed values for palindrome validation.
7.	Display the result and terminate the program.

## PROGRAM:
 ```
/*
Program to implement a Wrapper Class using Java
Developed by: Yashwanth K
RegisterNumber: 212224040369
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

public class PalindromeCheck{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int num = sc.nextInt();
        String original = Integer.toString(num);
        String reversed = new StringBuilder(original).reverse().toString();
        if(original.equals(reversed)){
            System.out.print(original+" is a palindrome number.");
        } else {
            System.out.println(original+" is not a palindrome number.");
            System.out.println("Reversed Number: "+reversed);
        }
    }
}
```

## OUTPUT:

<img width="614" height="220" alt="image" src="https://github.com/user-attachments/assets/ced50657-c80d-4b6a-91aa-eeab2dbdb7f9" />

## RESULT:

Thus the output is executed successfully.
