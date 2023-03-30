# javabootcamp
import java.util.*;
class Main{
    int a,b,c;
    public int sum(int a,int b){
        c=a+b;
        return c;
    }
    public static void main(String[] args){
 int a,b;
 Scanner c= new Scanner(System.in);
        System.out.println("enter 1st num");
        a=c.nextInt();
        System.out.println("enter 2nd num");
        b=c.nextInt();
        Main r=new Main();
        System.out.println("sum of two num is "+r.sum(a,b));
    }
}
