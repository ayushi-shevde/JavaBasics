# JavaBasics
#even odd program
import java.util.Scanner;

public class EvenOdd {
    public static void main(String[] args){
        //even odd
        ///2==0
        System.out.println("Enter the number: ");
        Scanner num=new Scanner(System.in);
        int num1=num.nextInt();
       if (num1%2==0){
           System.out.println("Number is Even");
       }
       else
           System.out.println("Number is odd");
    }
}


