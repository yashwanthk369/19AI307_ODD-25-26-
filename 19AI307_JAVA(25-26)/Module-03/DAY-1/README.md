# Ex.No:3(A) INHERITANCE AND AGGREGATION

## QUESTION:
Create a Super class Vehicle with fields brand (String) and speed (int). Create a subclass Car that inherits from Vehicle and adds a field fuelType (String).Implement a method in Car called displayInfo() that prints the vehicle's brand, speed, and fuel type.

## AIM:
To implement inheritance by creating a superclass Vehicle and a subclass Car, and to display the brand, speed, and fuel type using an overridden method.

## ALGORITHM :

1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create the Vehicle class with fields brand and speed, and initialize them using a constructor.
4.	Create the Car subclass extending Vehicle and add the fuelType field with its constructor.
5.	Override the display method in Car to show brand, speed, and fuel type.
6.	Read brand, speed, and fuel type from the user.
7.	Create a Car object and call the display method.
8.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Inheritance and Aggregation using Java
Developed by: Yashwanth K 
RegisterNumber: 212224040369 
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

class Vehicle {
    
    String brand;
    int speed;
    
    Vehicle(String brand,int speed) {
        
        this.brand = brand;
        this.speed = speed;
        
    }
    
    void display() {
        
        System.out.println("Brand: "+brand);
        System.out.println("Speed: "+speed+" km/h");
        
    }
}

class Car extends Vehicle {
    
    String type;
    
    Car(String brand,int speed,String type) {
        
        super(brand,speed);
        
        this.type = type;
        
    }
    
    void display() {
        
        super.display();
        
        System.out.println("Fuel Type: "+type);
        
    }
}

public class Main {
    
    public static void main(String[] args) {
        
        Scanner scan = new Scanner(System.in);
        
        String brand = scan.next();
        int speed = scan.nextInt();
        String type = scan.next();
        
        Car obj = new Car(brand,speed,type);
        
        obj.display();
        
    }
}
```

## OUTPUT:

<img width="549" height="313" alt="image" src="https://github.com/user-attachments/assets/a5ec1d6a-b3bc-47d8-bdab-73d2fbfe8028" />

## RESULT:

Thus the output is executed successfully.
