# Java Program to Calculate the Average of Three Numbers

```
import java.util.Scanner;

public class AverageOfThree {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        // Prompt the user to enter three numbers
        System.out.print("Enter the first number (A): ");
        double A = sc.nextDouble();

        System.out.print("Enter the second number (B): ");
        double B = sc.nextDouble();

        System.out.print("Enter the third number (C): ");
        double C = sc.nextDouble();

        // Calculate the average
        double average = (A + B + C) / 3;

        // Output the average
        System.out.println("The average of " + A + ", " + B + ", and " + C + " is: " + average);

        // Close the scanner
        sc.close();
    }
}
```

### Example Output

```
Enter the first number (A): 10
Enter the second number (B): 20
Enter the third number (C): 30
The average of 10.0, 20.0, and 30.0 is: 20.0
```
