# Area-of-Square-Ractangle-Triangle-and-circle
/*Area of Tiangle and circle--
  1.  Square: A=S² (s square)
  2.  Ractangle :A=lW
  3.  Triangle : A= 1/2 * bh
  4.  circle: A=πr² (r square)
*/

import java.util.Scanner;
class Main {
   public static void main (String [] args){
       Scanner sc = new Scanner(System.in);
       
       //Applying Square --
          System.out.println("Square---");
       double side, area;
       System.out.print("Enter the Length of Side:");
       side=sc.nextDouble();
        area=side*side;
        System.out.println("Area of  the side of length:"+area);
        
        //Applying Ractangle: A=LW --
        System.out.println("Ractangle---");
       double length,width;
       area=0;
       System.out.print("Enter the Length of Ractangle:");
       length=sc.nextDouble();
       System.out.print("Enter the width of Ractangle:");
       width=sc.nextDouble();
        area=length* width;
        System.out.println("Area of  Ractangle:"+area);
        
         //Applying Triangle: A=1/2 *BH --
        System.out.println("Triangle---");
       double height,base;
       area=0;
       System.out.print("Enter the Base of Triangle:");
       base=sc.nextDouble();
       System.out.print("Enter the Height of Triangle:");
       height=sc.nextDouble();
        area=0.5*base* height;
        System.out.println("Area of  Triangle:"+area);
        
        //Applying circle: A=πr² --
        System.out.println("Circle---");
       double radius;
       area=0;
       System.out.print("Enter the Radius of Circle:");
       radius=sc.nextDouble();
        area=3.1416*radius*radius;
        System.out.println("Area of  Circle:"+area);
   
    }
}
