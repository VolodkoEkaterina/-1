import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    Scanner in=new Scanner(System.in);
	    String s= in.nextLine();
	    s=s.replace(" ","");
	    String[] sub= s.split("[*/+-]");
	    int a = Integer.parseInt(sub[0]);
	    int b = Integer.parseInt(sub[1]);
	    if (s.contains("+")){
	        System.out.println(a+b);
	    }else if (s.contains("-")){
	        System.out.println(a-b);
	    }else if (s.contains("*")){
	        System.out.println(a*b);
	    }else if (s.contains("/")){
	        double c=a;
	        double d=b;
	        System.out.println(c/d);
	    } 
	}
}
