# example6_5
public class Example5_6
{
public static void main(String[] args)
{
int x, y;
Integer numl, num2;
numl = 8; //Autobox 8
num2 = 16; //Autobox 16 System.out.println("numl = " + numl + ", num2 = " + num2} ; 
X = 2 * numl + num2; //auto-unboxing
Y = numl + num2; //auto-unboxing System.out.println("x = " + x + ", y =" + y);
String s = new String("12");
x = Integer.parselnt(s);
s = s + numl.toString() + num2.toString();
System.out.println("Convert int to String and concate:" + s);
}
}
