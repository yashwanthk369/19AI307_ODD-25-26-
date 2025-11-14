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


<img src="//Screenshot 2025-11-13 161156.png"/>

## RESULT:





