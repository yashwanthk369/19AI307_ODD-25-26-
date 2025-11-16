# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:
Create a class Calculator with: One non-static method add(int a, int b) that returns the sum, One static method info() that says "Calculator is ready".

## AIM:
To develop a Java class Calculator containing a non-static method for addition and a static method that displays a readiness message.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define the Calculator class with a non-static method add(int a, int b) to return the sum.
4.	Define a static method info() to print “Calculator is ready”.
5.	Create an object to call the non-static add() method.
6.	Call the static info() method using the class name.
7.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Access Modifiers using Java
Developed by: Yashwanth K
RegisterNumber: 212224040369 
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

class Calculator{
    
    Calculator(){
        System.out.println("Calculator is ready");
    }
    
    public int add(int a,int b){
        return a+b;
    }
}

public class Main{
    public static void main(String[] args){
        Scanner scan = new Scanner(System.in);
        
        int a = scan.nextInt();
        int b = scan.nextInt();
        
        Calculator obj = new Calculator();
        
        int result = obj.add(a,b);
        
        System.out.print("Sum: "+result);
    }
}
```

## OUTPUT:

<img width="450" height="252" alt="image" src="https://github.com/user-attachments/assets/757eba95-db1a-447a-b353-7515d0f346f0" />

## RESULT:

Thus the output is executed successfully.
