import java.io.*;
import java.util.Scanner;
class mySaving {
public static void main(String[] args){
System.out.println("Enter Amount: ");
double result=0.0;
Scanner nesta= new Scanner (System.in);
int num= nesta.nextInt();
if(num>=0){
result+= num * 30;
System.out.println(result);
}
}
}
class detail extends mySaving {
public static void main (String[]args) throws ArithmeticException {
int a,b;
try{
a=0;
b=45/a;
}catch(ArithmeticException e){
System.out.println("Software maintenance);
}
}
}
