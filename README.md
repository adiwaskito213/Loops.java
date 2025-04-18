# loops.java
public class PrintOddNumbers {
    public static void main(String[] args) {
        System.out.println("Menampilkan bilangan ganjil");
        for (int i = 0; i < 12; i++) {
            if (i % 2 != 0) {
                System.out.print(i +" bilangan adalah adalah ganjil" + " " + "dan " );
            }else
                System.out.println( i + " bilangan adalah bilangan genap ");
        }
    }
}
