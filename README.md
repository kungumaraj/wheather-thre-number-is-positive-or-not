# import java.util.scanner;
public class compare {
public static void main(String args[])
{
scanner input=new scanner(System.in);
System.out.println("enter the number");
int number=input.nextInt();
if(number==0){
System.out.println("the number is zero");
}
else if(number>0)
{
System.out.println("the number is positive");
}
else
{
System.out.println("the number is negative");
}
}
