# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:

In a haunted house, lights turn on or off based on the hour of entry:
  If the hour is even and between 2 and 6 (inclusive), lights flicker.
  If the hour is odd and between 7 and 11, lights stay off.
  If the hour is 12, lights turn red.
  Otherwise, the house is dark.

## AIM:

To create a program that uses if-else statements to determine and print the light condition (flicker, off, red, or dark) inside a 
haunted house based on a user-inputted hour.


## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3. The program will first check for flickering lights: If the hour is even AND falls within the range of 2 to 6 (inclusive), the program prints "Lights flicker."
4. Next, it checks for lights off: If the previous condition wasn't met, the program then checks if the hour is odd AND falls within the range of 7 to 11. If this is true, it prints "Lights stay off."
5.Following that, it checks for red lights: If neither of the prior conditions was true, the program checks if the hour is exactly 12. If it is, the program prints "Lights turn red."
6.Finally, the program handles the default dark state: If none of the conditions above (flicker, off, or red) were met, the program executes the final else block and prints "The house is dark."
7.stop the program.

## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
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
        int a = scan.nextInt();
        if(a%2==0 & a>2 & a<6) {
            System.out.println("Lights flicker");
        }
        else if(a%2!=0 & a>=7 & a<11) {
            System.out.println("Lights off");
        }
        else if(a==12) {
            System.out.println("Lights red");
        }
        else {
            System.out.println("Dark house");
        }
    }
}
```

## OUTPUT:



## RESULT:

Thus the output is executed successfully.
