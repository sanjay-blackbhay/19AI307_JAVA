# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To create a java program that returns the sum of all the values in a 2D array.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `sum`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read `rows` and `cols` from user
-	c) Declare 2D array `arr[rows][cols]`
4.	Populate `arr` using nested loops with user input
5.	Initialize `sum` to `0`
6.	Calculate the sum of all elements in `arr` using nested loops
7.	Print "The sum of all values in the 2D array is: " + `sum`
8.	End



## PROGRAM:
 ```
/*
Program to implement a Single Array using Java
Developed by: Sanjay R
RegisterNumber: 212224060233
*/ 

```

## Sourcecode.java:


```
import java.util.Scanner;

class Circle {
    double area;

    // Constructor to calculate area
    Circle(double radius) {
        area = 3.14159 * radius * radius;
        System.out.printf("Area of the circle with radius %.2f is %.2f%n", radius, area);
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        if (sc.hasNextDouble()) {           // check if input exists
            double radius = sc.nextDouble();
            Circle c = new Circle(radius);  // constructor calculates & prints area
        }

        // Do not close Scanner in online judges (prevents hidden test failures)
    }
}


```

## OUTPUT:
<img width="1244" height="269" alt="514743086-45c2919b-7e80-4f6c-a3f4-ef56d86462bc" src="https://github.com/user-attachments/assets/4fc36c0d-3477-4461-b260-fa682950db43" />



## RESULT:
Thus the java program that returns the sum of all the values in a 2D array was executed successfully.
