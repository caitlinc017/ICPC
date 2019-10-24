import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner kb = new Scanner(System.in);
        while (kb.hasNext()) {
            int n = kb.nextInt();
            if (n == 0) break;
            boolean negative = n < 0;
            if (negative) n = -n;
            int sum = 0;
            for (int i = n; i > 0; i--) {
                sum += i;
            }
            if (negative) {
                sum = -sum + 1;
                n = -n;
            }
            System.out.println("N = " + n + "     Sum = " + sum);
            System.out.println();
        }
    }
}
