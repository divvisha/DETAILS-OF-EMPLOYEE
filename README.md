# EXPERIMENT-10 JAVA PROGRAM TO PRINT THE DETAILS OF AN EMPLOYEE.
 
## AIM:
   To write a java program to print the details of an employee.
   
## ALGORITHM:
   1. Create a class named 'Member' to get and print the salary of an employee.
   2. Then a class named 'Manager' and 'Employee' extends the class 'Member' for specialization and department details.
   3. Create a class named 'Job' to insert the details of an employees and salary to calculate using the class mentioned above.
   4. Using an object, get details of an employee in job class.
   5. Print the result.


## PROGRAM:

   public class Job<br>
   {<br>
    public static void main(String[] args)<br>
    {<br>
        Employee e1=new Employee();<br>
        e1.Name="Vishal";<br>
        e1.age=25;<br>
        e1.ph=54587;<br>
        e1.Address="92, TH road, Chennai";<br>
        e1.salary=60000;<br>
        Manager e2=new Manager();<br>
        e2.Name="Divya";<br>
        e2.age=26;<br>
        e2.ph=80424;<br>
        e2.Address="58, Kaladipet, Chennai";<br>
        e2.salary=75000;<br>
        System.out.println("Name : "+e1.Name);<br>
        System.out.println("Age : "+e1.age);<br>
        System.out.println("Phone Number : "+e1.ph);<br>
        System.out.println("Address : "+e1.Address);<br>
        e1.printSalary(e1.salary);<br>
        System.out.println("\n");<br>
        System.out.println("Name : "+e2.Name);<br>
        System.out.println("Age : "+e2.age);<br>
        System.out.println("Phone Number : "+e2.ph);<br>
        System.out.println("Address : "+e2.Address);<br>
        e2.printSalary(e2.salary);<br>
    }<br>
   }<br><br>
  public class Member<br>
  {<br>
    String Name;<br>
    int age;<br>
    int ph;<br>
    String Address;<br>
    int salary;<br>
    public void printSalary(int salary)<br>
    {<br>
        System.out.println("Salary : "+salary);<br>
    }<br>
  }<br><br>
  public class Employee extends Member<br>
  {<br>
    String specialization;<br>
    String department;<br>
  }<br><br>
  public class Manager extends Member<br>
  {<br>
    String specialization;<br>
    String department;<br>
  }<br>
  
  ## OUTPUT:
<img width="346" alt="java ex10 op" src="https://github.com/divvisha/INSERT-ELEMENT-INTO-ARRAY/assets/127508123/7234d809-59bc-4565-b1d4-77b580da2137">


  ## RESULT:
     Thus the program to create and print the details of an employee has been created and executed successfully.
