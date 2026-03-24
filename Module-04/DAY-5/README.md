# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Employee class that initializes name and designation, and then call getter methods in the main() method of another class (Sample) to display the values.

## ALGORITHM :

1.	Start the program.

2.	Define a class Employee:
    a.	  Declare two private string variables: name and designation.
  	
4.	Create a parameterized constructor in Employee:
5.	
6.	Accept two parameters: name and designation.
7.	
8.	Assign the parameters to the class fields.
9.	
10.	Define two getter methods in the Employee class:
     a.	getName() – returns the value of name.
     b.	getDesg() – returns the value of designation.
   	
12.	Create another class Sample with the main method.
13.	
14.	Inside the main method:
     a.	Create an object of Employee using the constructor and pass "John" and "Asst.Manager" as arguments.
     b.	Call getName() and store the result in a variable empName.
     c.	Call getDesg() and store the result in a variable empDesg.
   	
16.	Print the values of empName and empDesg.
17.	
18.	End the program


## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: Ramya S
RegisterNumber: 212222040130 
*/
```

## Sourcecode.java:
```
class Laptop {
    String brand;
    double price;
    public Laptop() {
        this.brand = "Apple";
        this.price = 42500.75;
    }

    public String getBrand() {
        return brand;
    }

    public double getPrice() {
        return price;
    }
}
public class Sample {
    public static void main(String[] args) {
        Laptop myLaptop = new Laptop();
        String laptopBrand = myLaptop.getBrand();
        System.out.println(laptopBrand);
        double laptopPrice = myLaptop.getPrice();
        System.out.println(laptopPrice);
    }
}
```






## OUTPUT:

<img width="488" height="323" alt="image" src="https://github.com/user-attachments/assets/b5d46d53-9772-4b4e-aba8-0e6c88618d95" />


## RESULT:
Thus, the  java program was successfully demonstrates the use of a parameterized constructor to initialize class fields.

 


