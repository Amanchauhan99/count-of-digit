# count-of-digit

package myProjects;

import java.util.Scanner;

public class CountDigitOf {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int count = 0;
		System.out.println("enter number");
		int n = sc.nextInt();
		while (n != 0) {
			n /= 10;
			++count;
		}
		System.out.println("number of digit "+count);
		
	}

}
