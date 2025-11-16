# Ex.No:3(C) ABSTRACTION

## QUESTION:
Create an abstract class Employee with method calculatePay(). Extend it to HourlyEmployee and SalariedEmployee.

## AIM:
To implement abstraction in Java by creating an abstract class Employee with an abstract method calculatePay(), and extending it through HourlyEmployee and SalariedEmployee classes.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define an abstract class Employee with the abstract method calculatePay().
4.	Create the HourlyEmployee subclass, store hours and rate, and implement calculatePay() to return hours × rate.
5.	Create the SalariedEmployee subclass, store salary, and implement calculatePay() to return the fixed salary.
6.	Read the employee type from the user.
7.	Based on the type, create the corresponding object and call calculatePay().
8.	Display the calculated pay.
9.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Abstraction using Java
Developed by: Yashwanth K 
RegisterNumber: 212224040369 
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

abstract class Employee {
    
    abstract double calculatePay();
    
}

class Hourly extends Employee{
    int hours;
    double rate;
    
    Hourly(int hours,double rate) {
        this.hours = hours;
        this.rate = rate;
    }
    
    double calculatePay() {
        return (double)hours * rate;
    }
}

class Salaried extends Employee{
    double salary;
    
    Salaried(double salary) {
        this.salary = salary;
    }
    
    double calculatePay() {
        return salary;
    }
}

public class Main{
    
    public static void main(String[] args){
        
        Scanner scan = new Scanner(System.in);
        
        int type = scan.nextInt();
        
        if(type==1){
            int hours = scan.nextInt();
            double salary = scan.nextDouble();
            Hourly obj = new Hourly(hours,salary);
            double result = obj.calculatePay();
            System.out.printf("%.2f",result);
            
        }
        
        else if(type == 2){
            double salary = scan.nextDouble();
            Salaried obj1 = new Salaried(salary);
            double result = obj1.calculatePay();
            System.out.printf("%.2f",result);
        }
        
        else {
            System.out.print("Invalid type");
        }
    }
}
```

## OUTPUT:

<img width="304" height="220" alt="image" src="https://github.com/user-attachments/assets/4bfba840-6ba6-4886-ac00-187ee61ca67c" />

## RESULT:

Thus the output is executed successfully.
