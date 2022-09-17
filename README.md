# java-
//print hello world 
class GFG {
	public static void main (String[] args) {
		System.out.println("hello world");
	}
}

## even or odd no.
package javafirst;
import java.util.Scanner;
public class JavaFirst {

	public static void main(String[] args) {
		Scanner sc = new Scanner (System.in);
		System.out.println("Please enter a no.");
		int n= sc.nextInt();
		if(n%2==0)
			{System.out.println("it is an even no.");
			
			}
		else
			{System.out.print("it is odd no");
			
			}
		//to find no. is even or odd

	}

}

## take a no.from user ,print sum of first n natural no ,if users enter a negative no.,show error and exit
package javafirst;
import java.util.Scanner;
public class JavaFirst {

	public static void main(String[] args) {
		Scanner sc = new Scanner (System.in);
		System.out.println("Please enter a no.");
		int n= sc.nextInt();
		if(n<0)
			{System.out.println("invalid input");
			return;
			}
		System.out.println(n*(n+1)/2);
		//to find no. is even or odd

	}

}
