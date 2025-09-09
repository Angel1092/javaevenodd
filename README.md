# javaevenodd
number counter.
/*
 * Author: Angel
 * Date: [9/9/2025]
 * 
 * Program: CountEvenOdd
 * Description:
 *   This Java program counts from 1 to 100 and prints whether each number is 
 *   even or odd. Additionally, it calculates and prints the total sum of all 
 *   numbers from 1 to 100.
 */
 
public class CountEvenOdd {
    public static void main(String[] args) {
        int sum = 0;

        for (int i = 1; i <= 100; i++) {
            // Check if the number is even or odd
            if (i % 2 == 0) {
                System.out.println(i + "\tEven");
            } else {
                System.out.println(i + "\tOdd");
            }

            // Add the number to the sum
            sum += i;
        }

        // Print the sum of numbers from 1 to 100
        System.out.println("\nTotal sum: " + sum);
    }
}
