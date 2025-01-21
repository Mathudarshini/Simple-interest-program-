
import java.util.Scanner;

public class SimpleInterest {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter principal amount: ");
        double principal = scanner.nextDouble();
        System.out.print("Enter rate of interest: ");
        double rate = scanner.nextDouble();
        System.out.print("Enter time in years: ");
        double time = scanner.nextDouble();
        scanner.close();

        double interest = (principal * rate * time) / 100;
        System.out.println("Simple Interest: " + interest);
    }
}


Output:


Enter principal amount: 1000
Enter rate of interest: 5
Enter time in years: 2
Simple Interest: 100.0
# Simple-interest-program-
