# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to reverse a given string.


## AIM:
To reverse a given string using Java.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the input string from the user.
4.	Initialize an empty string rev = "".
5.	Traverse the string from the last character to the first and append each character to rev.
6.	Display the reversed string.
7.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
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
        
        String string = scan.next();
        
        String reverse = "";
        
        for(int i=string.length() - 1;i>=0;i--) {
            reverse += string.charAt(i);
        }
        
        System.out.print("Reversed string: "+reverse);
    }
}
```

## OUTPUT:

<img width="529" height="201" alt="image" src="https://github.com/user-attachments/assets/b7ac9415-2062-45c1-8913-5bcbd9c94fc3" />

## RESULT:

Thus the output is executed successfully.
