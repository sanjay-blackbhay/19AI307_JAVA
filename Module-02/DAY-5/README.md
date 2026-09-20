# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
To write a Java program that reads an array size and elements from the user and then finds and prints the smallest element in the array.
## ALGORITHM :
1.	Start the program.
2.	Read the size of the array from the user.
3.	Declare an array of the given size.
4.	Read the array elements from the user.
5.	Initialize a variable min with the first element of the array.
6.	Traverse the array using a loop.
7.	Compare each element with min. If an element is smaller, update min.
8.	After the loop ends, print the smallest number.
9.	End the program.
	

## PROGRAM:
 ```
Program to implement a Single Array using Java
Developed by: Sanjay R
RegisterNumber: 212224060233
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

class Calculator {

    // Non-static method to add two numbers
    int add(int a, int b) {
        return a + b;
    }

    // Static method to display info
    static void info() {
        System.out.println("Calculator is ready");
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int num1 = sc.nextInt();
        int num2 = sc.nextInt();

        // Call static method
        Calculator.info();

        // Create object to call non-static method
        Calculator calc = new Calculator();
        int sum = calc.add(num1, num2);

        System.out.println("Sum: " + sum);

        // Do not close scanner in online judges
    }
}

```


## OUTPUT:

<img width="1242" height="363" alt="514743287-e1390ea8-ebc1-4046-adaa-9d6c83a69a27" src="https://github.com/user-attachments/assets/6e8a2ce6-4065-48a0-8137-ddbb320fe836" />


## RESULT:
Thus the java program successfully reads the array size and elements from the user and correctly finds and prints the smallest number in the array.



