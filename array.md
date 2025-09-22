# Arrays in java
 This java program gives basic idea about what arrays are\
 ```java
import java.util.*;
public class array
{
   public static void main(String[]args)
  {
  Scanner sc = new Scanner(System.in);
  int a[]= new int[5];
  int total;
  System.out.println("Enter 5 numbers:");

  a[0]=sc.nextInt();
  a[1]=sc.nextInt();
  a[2]=sc.nextInt();
  a[3]=sc.nextInt();
  a[4]=sc.nextInt();

 total= a[0]+a[1]+a[2]+a[3]+a[4] ;
 System.out.println("Sum:"+total);
 }
}
