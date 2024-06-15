# Java Program to Check if a Year is a Leap Year

```
import java.util.Scanner;

public class LeapYearChecker {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        // Prompt the user to enter a year
        System.out.print("Enter a year: ");
        int year = sc.nextInt();

        // Check if the year is a leap year
        boolean isLeapYear = false;

        if (year % 4 == 0) {
            if (year % 100 == 0) {
                // Year is divisible by 100, check if it is divisible by 400
                if (year % 400 == 0) {
                    isLeapYear = true;
                }
            } else {
                // Year is not divisible by 100, it is a leap year
                isLeapYear = true;
            }
        }

        // Output the result
        if (isLeapYear) {
            System.out.println(year + " is a leap year.");
        } else {
            System.out.println(year + " is not a leap year.");
        }

        // Close the scanner
        sc.close();
    }
}
```
### Example Output

```
Enter a year: 2024
2024 is a leap year.
```

```
Enter a year: 1900
1900 is not a leap year.
```
