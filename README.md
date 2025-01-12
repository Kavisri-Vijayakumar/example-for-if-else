import java.util.Scanner;
public class IfElseExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter a number: ");
        int number = scanner.nextInt();
        if (number % 2 == 0) {
            System.out.println("The number " + number + " is even.");
        } else {
            System.out.println("The number " + number + " is odd.");
        }
        scanner.close();
    }
}
output
Enter a number: 7
The number 7 is odd.
Enter a number: 4
The number 4 is even.
