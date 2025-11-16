# Ex.No:3(E) INNER CLASS

## QUESTION:
Write a Java program to create an inner class and access it from the outer class.


## AIM:
To demonstrate the use of an inner class in Java and access its methods through an instance of the outer class.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create an outer class containing an inner class.
4.	Define a method in the inner class to perform an action.
5.	Provide a method in the outer class to create an inner class object and call its method.
6.	Read user input inside main().
7.	Create an outer class object and access the inner class through it.
8.	Display the output.
9.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a InnerClass using Java
Developed by: Yashwanth K 
RegisterNumber: 212224040369 
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

class prog{
    
    class InnerClass{
        void greet(String name){
            System.out.print("Hello, "+name+"! This message is from the Inner Class.");
        }
    }
    
    void accessInner(String name){
        InnerClass inner = new InnerClass();
        inner.greet(name);
    }
    
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        String name = sc.nextLine();
        prog outer = new prog();
        outer.accessInner(name);
    }
}
```

## OUTPUT:

<img width="911" height="203" alt="image" src="https://github.com/user-attachments/assets/532d12bb-0ad4-4e83-ad11-c15d8eca0971" />

## RESULT:

Thus the output is executed successfully.
