# Ex.No:2(C)    SINGLE ARRAY

## AIM:
To create a java program to read 5 values and display the all 5 values from array using single dimensional array.

## ALGORITHM :
1.	Start the program.
2.	2.	Import the `Scanner` class from the `java.util` package
3.	Define a class named `ArrayExample`
4.	Inside the `main` method:
-	a) Create a `Scanner` object called `scanner` to take user input
-	b) Declare an integer array `values` of size 5
-	c) Use a `for` loop to iterate from `i = 0` to `i < 5`:
-   d) Take input from the user and store it in `values[i]`
5.	Print "Elements in Array are :"
6.	Use another `for` loop to iterate from `i = 0` to `i < 5`:
-	a) Print each element in `values` followed by a space
7.	Close the `scanner` to release resources
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


**import java.util.Scanner;

class Person {
    private String name;
    private int age;
    private String country;

    public String getName() {
        return name;
    }
    public void setName(String name) {
        this.name = name;
    }

    public int getAge() {
        return age;
    }
    public void setAge(int age) {
        this.age = age;
    }

    public String getCountry() {
        return country;
    }
    public void setCountry(String country) {
        this.country = country;
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        Person p = new Person();

        String name = sc.nextLine();
        int age = sc.nextInt();
        sc.nextLine(); // consume newline
        String country = sc.nextLine();

        p.setName(name);
        p.setAge(age);
        p.setCountry(country);

        // Print heading before details
        System.out.println("Person 1");
        System.out.println("Name: " + p.getName());
        System.out.println("Age: " + p.getAge());
        System.out.println("Country: " + p.getCountry());

        sc.close();
    }
}**

```






## OUTPUT:

<img width="1140" height="654" alt="511973818-d9cffbf8-79b2-493c-813a-eadd64aa66c3" src="https://github.com/user-attachments/assets/76a5be7e-f614-4951-bf25-b505cec4e777" />


## RESULT:
Thus, the Java program Thus the java program to read 5 values and display the all 5 values from array using single dimensional  was executed successfully.
