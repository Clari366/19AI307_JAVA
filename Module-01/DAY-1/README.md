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
Developed by: CLARISSA K
RegisterNumber:  212224230047
*/
```

## Sourcecode.java:

```
class Student
{
    String name;
    String address;
}
public class Main
{
    public static void main(String[] args)
   {
        Student obj= new Student();        
        obj.name="John";
        obj.address="Chennai";
        System.out.println(obj.name+" "+obj.address);
    }
}
```





## OUTPUT:

<img width="401" height="178" alt="437386419-8072b3cc-b32c-4e47-8384-c7b28682bf80" src="https://github.com/user-attachments/assets/08241b03-fab4-4463-8077-d11cc771d47a" />


## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
