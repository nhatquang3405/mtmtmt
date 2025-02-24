
  import java.util.Scanner;

public class SumSeries {
    public static int calculateSum(int N) {
        int S = 0;
        for (int i = 1; i <= N; i++) {
            S += i * 11;
        }
        return S;
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Nhập N: ");
        int N = scanner.nextInt();
        scanner.close();
        
        int result = calculateSum(N);
        System.out.println("Tổng S = " + result);
    }
}

