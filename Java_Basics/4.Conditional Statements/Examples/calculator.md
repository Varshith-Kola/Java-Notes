# Java Program for a Simple Calculator

```
import java.util.Scanner;

public class Calculator {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        // Prompt the user to enter two numbers
        System.out.print("Enter the first number: ");
        double num1 = sc.nextDouble();

        System.out.print("Enter the second number: ");
        double num2 = sc.nextDouble();

        // Prompt the user to enter an operator
        System.out.print("Enter an operator (+, -, *, /): ");
        char operator = sc.next().charAt(0);

        double result;

        // Perform the calculation based on the operator
        switch (operator) {
            case '+':
                result = num1 + num2;
                System.out.println(num1 + " + " + num2 + " = " + result);
                break;
            case '-':
                result = num1 - num2;
                System.out.println(num1 + " - " + num2 + " = " + result);
                break;
            case '*':
                result = num1 * num2;
                System.out.println(num1 + " * " + num2 + " = " + result);
                break;
            case '/':
                // Check if the divisor is not zero
                if (num2 != 0) {
                    result = num1 / num2;
                    System.out.println(num1 + " / " + num2 + " = " + result);
                } else {
                    System.out.println("Error: Division by zero is not allowed.");
                }
                break;
            default:
                System.out.println("Error: Invalid operator. Please enter one of +, -, *, /.");
                break;
        }

        // Close the scanner
        sc.close();
    }
}
```
### Example Output

```
Enter the first number: 10
Enter the second number: 5
Enter an operator (+, -, *, /): *
10.0 * 5.0 = 50.0
```

This program takes two numbers and an operator as input from the user and performs the corresponding arithmetic operation using a switch statement. If an invalid operator is entered, it displays an error message. If division by zero is attempted, it also displays an appropriate error message.
