# java-standard-input-standard-output
import java.util.Scanner;

public class Stdinout {

    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        
        Double d = scan.nextDouble();
        int i = scan.nextInt();
        scan.nextLine();
        String s = scan.nextLine();

        System.out.println("String: " + s);
        System.out.println("Double: " + d);
        System.out.println("Int: " + i);
    }
}
