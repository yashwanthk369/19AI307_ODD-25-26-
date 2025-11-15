# Ex.No:2(B) METHODS

## QUESTION:
Write a Java program with instance method calculateSum() that sums elements of an integer array. Class name is ArrayOps. Return type is int.


## AIM:
To create a Java class ArrayOps with an instance method calculateSum() that returns the sum of all elements in an integer array.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the array size and elements from the user.
4.	Store the array inside the ArrayOps class.
5.	Use the calculateSum() method to iterate through the array and accumulate the total.
6.	Return the final sum and display it to the user.
7.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Methods using Java
Developed by: Yashwanth K
RegisterNumber: 212224040369  
*/
```

## SOURCE CODE:

```
import java.util.Scanner;
public class ArrayOps {

    public int calculateSum(int [] arr) {
        int count = 0;
        for(int i=0;i<arr.length;i++){
            count += arr[i];
        }
        return count;
    }

    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int Size = scan.nextInt();
        int[] numbers = new int[Size];
        for(int i=0;i<numbers.length;i++) {
            numbers[i] = scan.nextInt();
        }
        
        ArrayOps obj = new ArrayOps();
        
        int result = obj.calculateSum(numbers);
        
        
        System.out.println(result);
    }
}
```
## OUTPUT:

<img width="316" height="147" alt="image" src="https://github.com/user-attachments/assets/bc8cfda2-633d-4889-8ed1-9b4f1860211f" />

## RESULT:

Thus the output is executed successfully.
