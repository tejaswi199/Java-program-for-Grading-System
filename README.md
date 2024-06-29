
import java.util.Scanner;
public class main{
    public static void main(String [] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter marks:");
        int m=sc.nextInt();
        if(m>100 || m<0){
            System.out.println("Invalid marks");
        }
        else if(90<=m && m<=100){
            System.out.println("Grade A");
        }
        else if(80<=m && m<=89){
            System.out.println("Grade B");
        }
        else if(70<=m && m<=79){
            System.out.println("Grade C");
        }
        else if(60<=m && m<=69){
            System.out.println("Grade D");
        }
        else{
            System.out.println("Grade F");
        }
    }
}
