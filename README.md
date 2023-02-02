java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner calculator = new Scanner(System.in);

        System.out.println("Введите своё имя >");
        String name = calculator.next();
        System.out.println("Привет, " + name + " :)");

        System.out.println("Введите аргумент 1 >");
        double arg1 = calculator.nextInt();

        System.out.println("Введите ");
        double arg2 = calculator.nextInt();

        double result = arg1 + arg2;
        System.out.println("Ваш резльтат :" + arg1 + "+" + arg2 + "=" + result);

        double result1 = arg1 * arg2;
        System.out.println("Ваш резльтат :" + arg1 + "*" + arg2 + "=" + result1);

        double result2 = arg1 / arg2;
        System.out.println("Ваш резльтат :" + arg1 + "/" + arg2 + "=" + result2);

        double result3 = arg1 + arg2;
        System.out.println("Ваш резльтат :" + arg1 + "-" + arg2 + "=" + result3);
    }
}
