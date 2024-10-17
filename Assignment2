import java.util.*;
class Complex_No {
 float real, img;
 public Complex_No() {
 real = 0;
 img = 0;
 }
 public Complex_No(float a, float b) {
 real = a;
 img = b;
 }
 public void Display(Complex_No C1, Complex_No C2) {
 System.out.println("First complex number is = (" + C1.real + ") + (" + C1.img + ")i");
 System.out.println("Second complex number is = (" + C2.real + ") + (" + C2.img + ")i");
 }
 public void AddNumbers(Complex_No C1, Complex_No C2) {
 float real = C1.real + C2.real;
 float img = C1.img + C2.img;
 System.out.println("Addition is = (" + real + ") + (" + img + ")i");
 }
 public void SubNumbers(Complex_No C1, Complex_No C2) {
 float real = C1.real - C2.real;
 float img = C1.img - C2.img;
 System.out.println("Subtraction is = (" + real + ") + (" + img + ")i");
 }
 public void MultiNumbers(Complex_No C1, Complex_No C2) {
 float real = (C1.real * C2.real - C1.img * C2.img);
 float img = (C1.real * C2.img + C1.img * C2.real);
 System.out.println("Multiplication is = (" + real + ") + (" + img + ")i");
 }
 public void DivNumbers(Complex_No C1, Complex_No C2) {
 float denominator = (C2.real * C2.real + C2.img * C2.img);
 float real = (C1.real * C2.real + C1.img * C2.img) / denominator;
 float img = (C1.img * C2.real - C1.real * C2.img) / denominator;
 System.out.println("Division is = (" + real + ") + (" + img + ")i");
 }
}
public class Ass__1 {
 public static void main(String[] args) {
 float num1, num2;
 Complex_No cal = new Complex_No();
 Scanner Sc = new Scanner(System.in);
 System.out.println("Enter the first complex number in a+bi format: ");
 System.out.print("Enter real part of first number: ");
 num1 = Sc.nextFloat();
 System.out.print("Enter imaginary part of first number: ");
 num2 = Sc.nextFloat();
 Complex_No Com1 = new Complex_No(num1, num2);
 System.out.println("Enter the second complex number in a+bi format: ");

 System.out.print("Enter real part of second number: ");

 num1 = Sc.nextFloat();

 System.out.print("Enter imaginary part of second number: ");

 num2 = Sc.nextFloat();

 Complex_No Com2 = new Complex_No(num1, num2);

 Sc.close();

 System.out.println();

 cal.Display(Com1, Com2);

 System.out.println();

 cal.AddNumbers(Com1, Com2);

 cal.SubNumbers(Com1, Com2);

 cal.MultiNumbers(Com1, Com2);

 cal.DivNumbers(Com1, Com2);

 }

}
 
