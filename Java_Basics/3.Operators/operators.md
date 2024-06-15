# 3.Operators

Operators in Java are special symbols that perform operations on variables and values. Java provides a rich set of operators to manipulate variables. These operators can be classified into several types:

1. **Arithmetic Operators**
2. **Relational Operators**
3. **Logical Operators**
4. **Assignment Operators**

### 1. Arithmetic Operators

Arithmetic operators are used to perform common mathematical operations such as addition, subtraction, multiplication, and division.

#### Types of Arithmetic Operators:
- `+` (Addition)
- `-` (Subtraction)
- `*` (Multiplication)
- `/` (Division)
- `%` (Modulus)

#### Example Program:
```java
public class ArithmeticOperators {
    public static void main(String[] args) {
        int a = 10;
        int b = 5;

        // Addition
        int sum = a + b;
        System.out.println("Sum: " + sum);

        // Subtraction
        int difference = a - b;
        System.out.println("Difference: " + difference);

        // Multiplication
        int product = a * b;
        System.out.println("Product: " + product);

        // Division
        int quotient = a / b;
        System.out.println("Quotient: " + quotient);

        // Modulus
        int remainder = a % b;
        System.out.println("Remainder: " + remainder);
    }
}
```

**Output:**
```
Sum: 15
Difference: 5
Product: 50
Quotient: 2
Remainder: 0
```

### 2. Relational Operators

Relational operators are used to compare two values. The result of a relational operation is a boolean value (`true` or `false`).

#### Types of Relational Operators:
- `==` (Equal to)
- `!=` (Not equal to)
- `>` (Greater than)
- `<` (Less than)
- `>=` (Greater than or equal to)
- `<=` (Less than or equal to)

#### Example Program:
```java
public class RelationalOperators {
    public static void main(String[] args) {
        int a = 10;
        int b = 5;

        // Equal to
        System.out.println("a == b: " + (a == b));

        // Not equal to
        System.out.println("a != b: " + (a != b));

        // Greater than
        System.out.println("a > b: " + (a > b));

        // Less than
        System.out.println("a < b: " + (a < b));

        // Greater than or equal to
        System.out.println("a >= b: " + (a >= b));

        // Less than or equal to
        System.out.println("a <= b: " + (a <= b));
    }
}
```

**Output:**
```
a == b: false
a != b: true
a > b: true
a < b: false
a >= b: true
a <= b: false
```

### 3. Logical Operators

Logical operators are used to combine multiple boolean expressions or values and return a boolean result.

#### Types of Logical Operators:
- `&&` (Logical AND)
- `||` (Logical OR)
- `!` (Logical NOT)

#### Example Program:
```java
public class LogicalOperators {
    public static void main(String[] args) {
        boolean x = true;
        boolean y = false;

        // Logical AND
        System.out.println("x && y: " + (x && y));

        // Logical OR
        System.out.println("x || y: " + (x || y));

        // Logical NOT
        System.out.println("!x: " + (!x));
        System.out.println("!y: " + (!y));
    }
}
```

**Output:**
```
x && y: false
x || y: true
!x: false
!y: true
```

### 4. Assignment Operators

Assignment operators are used to assign values to variables.

#### Types of Assignment Operators:
- `=` (Simple assignment)
- `+=` (Add and assign)
- `-=` (Subtract and assign)
- `*=` (Multiply and assign)
- `/=` (Divide and assign)
- `%=` (Modulus and assign)

#### Example Program:
```java
public class AssignmentOperators {
    public static void main(String[] args) {
        int a = 10;

        // Simple assignment
        int b = a;
        System.out.println("b = a: " + b);

        // Add and assign
        b += 5;
        System.out.println("b += 5: " + b);

        // Subtract and assign
        b -= 3;
        System.out.println("b -= 3: " + b);

        // Multiply and assign
        b *= 2;
        System.out.println("b *= 2: " + b);

        // Divide and assign
        b /= 4;
        System.out.println("b /= 4: " + b);

        // Modulus and assign
        b %= 3;
        System.out.println("b %= 3: " + b);
    }
}
```

**Output:**
```
b = a: 10
b += 5: 15
b -= 3: 12
b *= 2: 24
b /= 4: 6
b %= 3: 0
```

These operators are fundamental in Java and are used in various operations and expressions within your code.
