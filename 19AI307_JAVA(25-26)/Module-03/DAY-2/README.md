# Ex.No:3(b) POLYMORPHISM

## QUESTION:
Write a Java program that calculates the area of different shapes using method overloading. Create a class AreaCalculator with:

## AIM:
To implement method overloading in Java by creating an AreaCalculator class that computes the area of multiple shapes (square, rectangle, circle) using different method signatures.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define the AreaCalculator class with three overloaded area() methods for square, rectangle, and circle.
4.	Read side, length, breadth, and radius values from the user.
5.	Create an instance of AreaCalculator.
6.	Invoke the appropriate overloaded area() methods based on input parameters.
7.	Display the computed areas.
8.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Polymorphism using Java
Developed by: Yashwanth K 
RegisterNumber: 212224040369  
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

class AreaCalculator {
    
    void area(int side) {
        
        int area = (int)Math.pow(side,2);
        
        System.out.println("Area of square: "+area);
        
    }
    
    void area(int length,int breadth) {
        
        int area = length * breadth;
        
        System.out.println("Area of rectangle: "+area);
        
    }
    
    void area(double radius) {
        
        double area = Math.PI * Math.pow(radius,2);
        
        System.out.println("Area of circle: "+area);
        
    }
}

public class Main {
    
    public static void main(String[] args) {
        
        Scanner scan = new Scanner(System.in);
        
        int side = scan.nextInt();
        int length = scan.nextInt();
        int breadth = scan.nextInt();
        double circle = scan.nextDouble();
        
        AreaCalculator obj = new AreaCalculator();
        
        obj.area(side);
        
        obj.area(length,breadth);
        
        obj.area(circle);
        
    }
}
```

## OUTPUT:

<img width="672" height="307" alt="image" src="https://github.com/user-attachments/assets/680f8af4-3977-47cc-97c5-65a5ea4e3db6" />

## RESULT:

Thus the output is executed successfully.
