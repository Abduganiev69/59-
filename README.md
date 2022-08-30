# 59-
Проверьте делимость
public class Main
{
    public static void main(String[] args) {
         java.util.Scanner myscanner= new java.util.Scanner(System.in);
        int a = myscanner.nextInt();
        int b = myscanner.nextInt();
        int x;
            if (b < a){
             x = a;
             a = b;
             b = x;
              }else{
            
        } 
             if (a / b == 0 ) {
              System.out.println(1);
             }else{
             System.out.println(2);
        }
    }
}
