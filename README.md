import java.util.Scanner;

public class calculator
{
    public void add(int a, int b)
    {
        int value = a;
        int value0 = b;
        int result = a + b;
        System.out.println(result);
    }

    public void sum()
    {
        int a = 1;
        int b = 2;
        int result = a + b;
        System.out.println(result);
    }

    public void div(int a, int b)
    {
        int value = a;
        int value0 = b;
        int result = a / b;
        System.out.println(result);
    }

    public void multiply(int a, int b)
    {
        int value = a;
        int value0 = b;
        int result = a * b;
        System.out.println(result);
    }

    public void subtract(int a, int b)
    {
        int value = a;
        int value0 = b;
        int result = a - b;
        System.out.println(result);
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        calculator calc = new calculator();

        System.out.println("Enter the first number: ");
        int a = sc.nextInt();

        System.out.println("Enter the second number: ");
        int b = sc.nextInt();

        // Call the functions using user inputs
        calc.add(a, b);
        calc.subtract(a, b);
        calc.multiply(a, b);
        calc.div(a, b);
        calc.sum();
    }
}
