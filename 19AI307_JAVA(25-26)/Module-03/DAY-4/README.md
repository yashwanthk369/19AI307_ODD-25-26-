# Ex.No:3(D)    INTERFACE 

## QUESTION:
You are programming bots that analyze weather data. Each bot must implement a common interface and give a prediction.

## AIM:
To implement an interface in Java by creating a common Bot interface for weather-prediction bots and developing multiple bot classes that provide specific predictions.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define an interface Bot with the method prediction().
4.	Implement the interface in SunBot and provide temperature-based predictions.
5.	Implement the interface in RainBot and provide temperature-based predictions.
6.	Read temperature and bot type from the user.
7.	Create the appropriate bot object and call its prediction() method.
8.	Display the prediction result.
9.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Interface using Java
Developed by: Yashwanth K 
RegisterNumber: 212224040369
*/
```

## SOURCE CODE:

```

import java.util.Scanner;

interface Bot {
	
	public void prediction();
	
}

class SunBot implements Bot {
	
	int temperature;
	
	SunBot(int temperature) {
		this.temperature = temperature;
	}
	
	public void prediction() {
		if(temperature > 30) {
			System.out.print("HOT");
		}
		else {
			System.out.print("MODERATE");
		}
	}
}

class RainBot implements Bot {
	
	int temperature;
	
	RainBot(int temperature) {
		this.temperature = temperature;
	}
	
	public void prediction() {
		if(temperature < 20) {
			System.out.print("COLD");
		}
		else {
			System.out.print("WARM");
		}
	}	
}
	
public class Main{
	
	public static void main(String[] args) {
		
		Scanner scan = new Scanner(System.in);
		
		int temperature = scan.nextInt();
		
		int type = scan.nextInt();
		
		if(type == 1) {
			SunBot obj = new SunBot(temperature);
			obj.prediction();
		}
		
		else if(type == 2) {
			RainBot obj1 = new RainBot(temperature);
			obj1.prediction();
		}
		
		else {
			System.out.print("Invalid type");
		}
	}
	
}
```

## OUTPUT:

<img width="271" height="128" alt="image" src="https://github.com/user-attachments/assets/aa5fd466-3dd3-4a50-bdc2-0d5223ccbc7d" />

## RESULT:

Thus the output is executed successfully.
