import java.io.*;
import java.util.Scanner;


public class day
{


    public static void main(String[] args)
    {
       
    Scanner sc=new Scanner(System.in);
    String s1="monday";
    String s2="tuesday";
    String s3="wednesday";
    String s4="hrusday";
    String s5="friday";
    String s6="saturday";
    String s7="sunday";
    String days=sc.nextLine();
   
    if(s7.equals(days))
    {
        System.out.println("false");
    }
    else if((s1.equals(days))||(s2.equals(days))||(s3.equals(days))||(s4.equals(days))||(s5.equals(days))||(s6.equals(days)))
    {
        System.out.println("true");
    }
    else
    {
        System.out.println("invalid");
    }
   
   }
   

}
