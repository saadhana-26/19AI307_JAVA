# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program to print student details (name and age), where age is the same for all students. Use a static variable to represent the age and demonstrate its use in accessing a shared value across all class objects

## ALGORITHM :
1.	Start the program.
2.	Create a class named Student.
3.	Declare a static variable age in the Student class.
4.	Declare an instance variable name.
5.	Create a constructor to initialize the student's name.
6.	Define a method displayDetails() to print the student's name and age.
7.	In the main method:
I.	Assign a value to the static variable age.
II.	Create multiple Student objects with different names.
III.	Call the displayDetails() method for each student.
8.	End the program.



## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: Janani G
RegisterNumber:  212224100022
class Student {
    static int age;
    String name;

    Student(String name) {
        this.name = name;
    }

    void displayDetails() {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
    }
}

public class Main {
    public static void main(String[] args) {
        Student.age = 20;

        Student student1 = new Student("John");
        Student student2 = new Student("David");
        Student student3 = new Student("Alice");

        student1.displayDetails();
        student2.displayDetails();
        student3.displayDetails();
    }
}
*/
```

## Sourcecode.java:







## OUTPUT:

<img width="1907" height="936" alt="image" src="https://github.com/user-attachments/assets/093c233f-95cc-4d52-9346-72949e7336a6" />


## RESULT:
Thus, the Java program for the concept of using a static variable for shared data was correctly implemented and verified successfully. 

