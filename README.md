# Shivani
Write a simple java program for Addition , Subtraction, Division , Multiplication


import java.util.Scanner;
		 
public class ASDM
{
    public static void main(String args[])
    {
       int a, b, c;
       Scanner scan = new Scanner(System.in);
	   
       System.out.print("Enter Two Numbers : ");
       a = scan.nextInt();
       b = scan.nextInt();
	   
       c = a + b;
       System.out.println("Addition = " +c);
	   
       c = a - b;
       System.out.println("Subtraction = " +c);
	   
       c= a * b;
       System.out.println("Multiplication = " +c);
	   
       c = a / b;
       System.out.println("Division = " +c);
    }
}
