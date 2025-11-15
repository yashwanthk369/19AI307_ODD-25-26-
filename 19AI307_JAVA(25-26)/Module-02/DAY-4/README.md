# Ex.No:2(D) VARIABLE SCOPE AND CONSTRUCTOR

## QUESTION:
Write a Java program to create a class called Smartphone with private instance variables brand, model, and storageCapacity. Provide public getter and setter methods to access and modify these variables. Add a method called increaseStorage() that takes an integer value and increases the storageCapacity by that value.

## AIM:
To implement a Java class Smartphone using private variables, a constructor for initialization, and methods to modify and display the device’s storage details.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read brand, model, storage capacity, and extra storage from the user.
4.	Initialize the object using a constructor that sets brand, model, and storage.
5.	Use the increaseStorage() method to add extra storage.
6.	Display the updated smartphone details using a dedicated method.
7.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Variable scope and Constructor using Java
Developed by: Yashwanth K 
RegisterNumber: 212224040369
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

class prog {
    private String brand;
    private String model;
    private int storageCapacity;

    
    public String getBrand() {
        return brand;
    }

    public String getModel() {
        return model;
    }

    public int getStorageCapacity() {
        return storageCapacity;
    }

    
    public void setBrand(String brand) {
        this.brand = brand;
    }

    public void setModel(String model) {
        this.model = model;
    }

    public void setStorageCapacity(int storageCapacity) {
        this.storageCapacity = storageCapacity;
    }

   
    public void increaseStorage(int value) {
        if (value > 0) {
            this.storageCapacity += value;
        }
    }

    
    public void display() {
        System.out.println("Brand: " + brand);
        System.out.println("Model: " + model);
        System.out.println("Updated Storage Capacity: " + storageCapacity + " GB");
        System.out.println("------------------------------");
    }
    
    public static void main(String[] args){
    Scanner scan = new Scanner(System.in);
    String Brand = scan.nextLine();
    String Model = scan.nextLine();
    int Memory = scan.nextInt();
    int ExMemory = scan.nextInt();
    
    prog obj = new prog();
    
    obj.setBrand(Brand);
    obj.setModel(Model);
    obj.setStorageCapacity(Memory);
    obj.increaseStorage(ExMemory);
    
    obj.display();
    }
}
```

## OUTPUT:

<img width="770" height="370" alt="image" src="https://github.com/user-attachments/assets/9d4d966e-568c-4c74-9ec6-a764701ec706" />

## RESULT:

Thus the output is executed successfully.
