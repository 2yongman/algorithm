-----------------------------algorithm-------------------------------
public class ConditionalExam {
    public static void main(String[] argv) {
        scanner i = new scanner(system.in)
        int value = i.nextInt();
        if( value % 3 == 0 ) {
            System.out.println("value는 3의 배수입니다.");
        }
    }
}



-----------*찍기 문제------------

package ForTest;

import java.util.Scanner;

public class forTest {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int m = sc.nextInt();

        for(int i=0; i<n; i++){
            for(int j=0; j<m-1; j++){
                System.out.print("*");
            }
            System.out.println("*");
        }

    }
}

