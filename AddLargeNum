import java.math.BigInteger;
import java.util.Scanner;

/*
** Christian Gil S. Alaan
** CC 13.1 B - DATA STRUCTURES AND ALGORITHMS
** Midterm Exam Part II: Programming Problem 1
 */

public class Alaan_AddLargeNum {
    public static void main(String[] args) {
        try (Scanner scanner = new Scanner(System.in)) {
            System.out.println("\nInput Number of Test Cases:");
            int n = scanner.nextInt();
            BigInteger sum;


            for (int i = 0; i < n; i++) {

                System.out.println("\nInput x:");
                String input1 = scanner.next();
                System.out.println("Input y:");
                String input2 = scanner.next();


                BigInteger a = new BigInteger(input1);
                BigInteger b = new BigInteger(input2);


                sum = a.add(b);


                System.out.println("\nCase #"+(i+1) + ": " + sum);
            }
        }

        System.out.println("\n That is all. Thank you for using the program!");
    }
}
