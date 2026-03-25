public class Exec1b {
   private int a;
   private int b;
   private int d;

    public void rec(int a, int b, int d) {
        this.a = a;
        this.b = b;
        this.d = d;
    }
    public int A1() {
        return this.a * this.b;
    }
    public int A2() {
        return this.b * this.d;
    }


}

import java.util.Scanner;
public class Exec1 {
    public static void main(String args[]) {
        Scanner objScan = new Scanner(System.in);
        Exec1b objEx1 = new Exec1b();
        
        
        
        
    }
}
