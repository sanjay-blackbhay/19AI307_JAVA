# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To create a java program to read input and print length of the string in java.

## ALGORITHM :
1.  Start the Program.
2.	Import `Scanner` and define class `demo`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a line of text into `String` variable `str`
4.	Print "The size of the String is " + `str.length()`
5.	End




## PROGRAM:
 ```
/*
Program to implement a String and its Operations using Java
Developed by: DINESH SREE VATHSAN A
RegisterNumber: 212224060070
*/
```

## Sourcecode.java:

```
import java.util.Scanner;
public class Main {
	public static void main(String[] args)
	{
    	// Here str is a string object
   	Scanner sc = new Scanner(System.in);  // Create a Scanner object
   	String str = sc.nextLine();

 
    	System.out.println(
        	"The size of "
        	+ "the String is "
        	+ str.length());
	}
}
```





## OUTPUT:
<img width="726" height="282" alt="image" src="https://github.com/user-attachments/assets/dac1237a-2f4e-49a2-b102-f7a50344692f" />



## RESULT:

Thus the java Program to read input and print length of the string in java was executed successfully.
