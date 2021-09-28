# concatenate-of-tring
import java.util.Scanner;
public class Concatenatestr {
    public static void main(String args[]) {
        System.out.println("enter the string you want yo enter");
        String a, b;
        Scanner st = new Scanner(System.in);
        int n = 10;
        for (int i = 0; i < n; i++) {
            a = st.nextLine();
            b = st.nextLine();
            System.out.println("the strings you have entered are    " + a + "    " + b);
        }
    }
}
