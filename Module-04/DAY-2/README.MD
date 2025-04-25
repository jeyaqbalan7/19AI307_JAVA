# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To write a Java program for below situation, Student object contains member 'Stu_Id'. It contains object named course, which contains its own informations such as Degree, Branch, Year of Studying.

## ALGORITHM :

## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: Onteddu Sirisha
RegisterNumber: 212222230103
*/
```

## Sourcecode.java:
```

class Subject
{
    
    String subject1,subject2,subject3,subject4;
      //Write Your Code Here
      
    void dispSub(String subject1,String subject2,String subject3,String subject4)
    {
        System.out.println(subject1+" "+subject2+" "+subject3+" "+subject4);
         //Write Your Code Here
    }
}
class Student
{
    int Stu_Id;
    Subject obj = new Subject();
    
    //Write Your Code Here
    
    void disp(int id)
    {
        System.out.println(id);
        obj.dispSub("B.Tech","IT","Third","year");
        //Write Your Code Here
    }
}

public class Main
{
    public static void main(String[] args)
    {
        //Write Your Code Here
        Student obj = new Student();
        obj.disp(101);
        
    }
}
```


## OUTPUT:
```
Input      Expected                 Got
---        101                      101
           B.Tech IT Third year     B.Tech IT Third year
```
## RESULT:
Thus the Java program to implement the program for below situation, Student object contains member 'Stu_Id'. It contains object named course, which contains its own informations such as Degree, Branch, Year of Studying was  executed successfully.

