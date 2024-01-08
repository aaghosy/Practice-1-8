# Practice-1-8
package second_oneone;

import java.util.Scanner;

public class cashier {
	public static void main(String[] args) {
       Scanner in = new Scanner(System.in);
       int amount = in.nextInt();
       System.out.println(amount);
       System.out.println(amount>-10);
       System.out.println("charge"+(amount-10));
}
}
