# Creating the followig table using JAVA
![image](https://github.com/gpavithra673/Creating_table-java-/assets/93427264/efa697a8-41ea-49f0-9ea6-37cd7ea7c4c1)

## AIM:
### Create a table using java.
## PROCEDURE:
### 1.Import the required packages and create a class named EMPLOYEE.
### 2.Inside the new class declare the required variables that we are gonna use in the main class.
### 3.In the main class accept the inputs from the user and print them in the order.
### 4.Use SCANNER to accept the inputs and store them in the declared variable by creating a new object of the EMPLOYEE class.
### 5.Use the object and store them respectively.
## PROGRAM:
```
//NAME: PAVITHRA G
//ROLLNO: 212221240036
package q3;

import java.util.Scanner;
public class Main{
    public static void main(String[] args) {
        Scanner sc= new Scanner(System.in);
        Employee emp= new Employee();
        for(int i=0;i<3;i++)
        {
            emp.Name[i]=sc.next();
            emp.year[i]=sc.nextInt();
            emp.addr[i]=sc.next();
        }
        System.out.println("Name           Year of joining           Address");
        for(int i=0;i<3;i++)
        {
            System.out.println(emp.Name[i]+"\t\t\t\t"+"  "+emp.year[i]+"\t\t\t\t"+emp.addr[i]);
        }
    }
}

public class Employee{
    String Name[]=new String[20];
    int year[]=new int[50];
    String addr[]=new String[20];
}

```
## RESULT:
![image](https://github.com/gpavithra673/Creating_table-java-/assets/93427264/4b883353-55d7-43ed-bcac-d9156811e00a)
