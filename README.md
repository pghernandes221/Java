import java.util.Scanner;

/**
 *
 * @author user
 */
public class Ex2 {
    public static void main(String args[]){
        Scanner input = new Scanner(System.in);
        int n = input.nextInt();
        int mult=1;
        for(int i=n;i>=1;i--){
            
            mult=mult*i;
            
            
        }
        System.out.printf("%d",mult);
    }
}
