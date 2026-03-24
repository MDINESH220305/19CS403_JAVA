# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:
To implement a  Java Program to Find the Largest or Max Number in Array using has - a relationship.
## ALGORITHM :
1.	Start the program.
2.	Create a class ArrayData:
a.	Declare an integer array and a variable for size.
b.	Create a method to read array elements from the user.
3.	Create another class ArrayOperation:
a.	Create a method findMax() that accepts an ArrayData object.
b.	Loop through the array and find the largest element.
4.	In the main() method of a class Main:
a.	Create an object of ArrayData and read the input.
b.	Create an object of ArrayOperation and call findMax() by passing the ArrayData object.
5.	Display the largest number.
6.	End the program.



## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: Ramya S
RegisterNumber: 212222040130
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class TriangleArea {

    private double width;
    private double height;

    public void setWidth(double width) {
        this.width = width;
    }

    public void setHeight(double height) {
        this.height = height;
    }

    public double getArea() {
        return width * height;
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        TriangleArea triangle = new TriangleArea();
        double w = sc.nextDouble(); 
        double h = sc.nextDouble(); 
        triangle.setWidth(w);
        triangle.setHeight(h);
        System.out.println((int)triangle.getArea());
    }
}
```






## OUTPUT:

<img width="423" height="462" alt="image" src="https://github.com/user-attachments/assets/a8e4d808-802f-43e3-98d5-c146ee8da2eb" />


## RESULT:
Thus the java program to Find the Largest or Max Number in Array using has - a relationship was executed successfully. 

