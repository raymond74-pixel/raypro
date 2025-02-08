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
