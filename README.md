# task_1.7

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        Scanner scan = new Scanner(System.in);

        int a = scan.nextInt ();
        int b = scan.nextInt ();
        int c = scan.nextInt();

        System.out.print ("Объем бассейна = " + a*b*c*1000);

    }
}
