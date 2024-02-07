import java.util.Scanner;

public class Evenoddswitch {

	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		System.out.println("enetr a number");
		int num=sc.nextInt();
		switch(num%2)
		{
		case 0:
			System.out.println("even");
			break;
		case 1:
			System.out.println("odd");
			break;
		}

	}

}
