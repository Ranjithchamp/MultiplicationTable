# MultiplicationTable
import java.util.Scanner;

public class MultiplicationNumber {

	public static void main(String[] args) {
		Scanner get = new Scanner(System.in);
		System.out.println("enter number for multiplication :");
		int A = get.nextInt();
		for(int i=1;i<11;i++)
		{
			System.out.println(i+" * "+A+" = "+i*A);
		}
	}
}
