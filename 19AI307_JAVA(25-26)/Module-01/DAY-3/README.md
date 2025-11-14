# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:

a
## AIM:


## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	





## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: 
RegisterNumber:  
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









