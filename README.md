# EXP-1 java program to print the Arithmetic operations
# AIM:
To write a java program to print the Arithmetic operations like Addiction, Subtraction, Division, Remainder of two numbers.

# PROCEDURE:
1. Import required packages.
2. Declare main method with the signature "public static void main(String[] args)".
3. Get two numbers as input.
4. Perform operations like addition,subtraction,multiplication,division and modulus using the two inputs.
5. Print the output on display.

# PROGRAM:
```
import java.util.Scanner;
public class arithmetic {
    public static void main(String[] args) {
        int add,sub,mul,rem;
        float divide;
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        add=a+b;
        sub=a-b;
        mul=a*b;
        divide=a/b;
        rem=a%b;
        System.out.println("Sum="+add);
        System.out.println("Subtraction="+sub);
        System.out.println("Multiplication="+mul);
        System.out.println("Division="+divide);
        System.out.println("Remainder="+rem);
    }
}
```

# OUTPUT:
![image](https://github.com/Evangelin-Ruth/Arithmetic/assets/94219798/138bf301-dd4b-48b9-80ba-41083cda8c05)

# RESULT:
The java program to print the Arithmetic operations like Addiction, Subtraction, Division, Remainder of two numbers was successfully done.
