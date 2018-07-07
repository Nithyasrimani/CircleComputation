# CircleComputation
import java.util.Scanner;  

public class CircleComputation {   

   public static void main (String[] args) {
      
      double radius, diameter, circumference, area;
      Scanner in = new Scanner(System.in);  
      
      System.out.print("Enter the radius: ");  
      radius = in.nextDouble();  

      diameter = radius + radius;
      circumference = 2*3.14*radius;
      area = 3.14*radius*radius;
      
      System.out.println("Diameter is: " + String.format("%.2f", diameter));
      System.out.println("Circumference is: " + String.format("%.2f", circumference));
      System.out.println("Area is: " + String.format("%.2f", area));
   }
}
