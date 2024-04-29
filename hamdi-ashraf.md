``` java

import java.util.Scanner;

public class SumOfPositiveIntegers {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        
        long n;
        while (true) {
            System.out.println("Please enter a positive integer between 1 and 1,000,000,000:");
            n = scanner.nextLong();
            if (n >= 1 && n <= 1000000000) {
                break; // Exit the loop if the input is valid
            } else {
                System.out.println("Invalid input. Please enter a positive integer between 1 and 1,000,000,000.");
            }
        }

        
        long sum = (n * (n + 1)) / 2;

        
        System.out.println("The sum of all positive integers less than or equal to " + n + " is: " + sum);

        scanner.close();
    }
}
```