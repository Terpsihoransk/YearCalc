import java.util.Scanner;

public class Yearcalc {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Введите текущи год: ");

        int year;
        year = scanner.nextInt();
        if (year > 0) {
            System.out.println("Високосных дней: " + operate(year));
        }
    }

    public static int operate(int year) {
        return year/400 + year/4 - year/100;
    }
}
