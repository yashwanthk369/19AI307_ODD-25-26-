# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java Program to count Even and Odd Numbers in an Array.

## AIM:
To count the number of even and odd elements in an array using Java.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the array size and array elements from the user.
4.	Initialize two counters: evenCount = 0 and oddCount = 0.
5.	Traverse the array and increment evenCount for even numbers and oddCount for odd numbers.
6.	Display the values of evenCount and oddCount.
7.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: Yashwanth K 
RegisterNumber: 212224040369  
*/
```

## SOURCE CODE:

```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int Size = scan.nextInt();
        int Odd = 0;
        int Even = 0;
        int[] numbers = new int[Size];
        for(int i=0;i<numbers.length;i++) {
            numbers[i] = scan.nextInt();
            if(numbers[i] % 2 == 0) {
                Even += 1;
            }
            else {
                Odd += 1;
            }
        }
        System.out.println("Number of even elements: "+Even);
        System.out.println("Number of odd elements: "+Odd);
    }
}
```

## OUTPUT:

<img width="557" height="466" alt="image" src="https://github.com/user-attachments/assets/65f6b94c-c7e0-42bc-b67a-5ecf7d26b5b1" />

## RESULT:

Thus the output is executed successfully.
