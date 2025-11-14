# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:


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

#<img width="503" height="133" alt="image" src="https://github.com/user-attachments/assets/13738a14-1add-47fb-85fa-ade4e7f378ef" />
<img src="//Screenshot 2025-11-13 161156.png"/>

## RESULT:




