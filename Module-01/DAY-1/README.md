# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Janani G
RegisterNumber: 21222410002
import java.util.*;
class Student{
        String name;
        String address;
    Student(){
    name="John";
    address="chennai";
}
}
class Main {
    public static void main(String[] args) {
        Student obj=new Student();
        System.out.println("Name:"+obj.name);
        System.out.println("Address:"+obj.address);
    }
} 
*/
```

## Sourcecode.java:
```
class Student {
    String name;
    String address;

    Student() {
        name = "John";
        address = "Chennai";
    }
}

public class Sourcecode {
    public static void main(String[] args) {
        Student obj = new Student();

        System.out.println("Name: " + obj.name);
        System.out.println("Address: " + obj.address);
    }
}



```

## OUTPUT:

<img width="1917" height="942" alt="image" src="https://github.com/user-attachments/assets/3234aa5e-c4b3-4d4f-bc1b-f59708e87e7a" />


## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
