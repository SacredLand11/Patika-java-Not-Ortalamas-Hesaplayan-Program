# Patika-java-Not-Ortalamasi-Hesaplayan-Program
## Java kodu asagidadir.
import java.util.Scanner;
public class Giris {
    public static void main(String[] args) {
        int mat,fiz,kim,turk;

        Scanner sc = new Scanner(System.in);

        System.out.print("Mat not: ");
        mat = sc.nextInt();
        System.out.print("Fiz not: ");
        fiz = sc.nextInt();
        System.out.print("Kim not: ");
        kim = sc.nextInt();
        System.out.print("Turk not: ");
        turk = sc.nextInt();

        int toplam = (mat+fiz+kim+turk);
        double sonuc = toplam/4.0;
        System.out.println("Sonucunuz: " + sonuc);
    }
}
