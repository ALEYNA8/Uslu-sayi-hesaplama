# Uslu-sayi-hesaplama
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int taban, us, sonuc = 1;

        System.out.print("Taban değerini giriniz: ");
        taban = scanner.nextInt();

        System.out.print("Üs değerini giriniz: ");
        us = scanner.nextInt();

        for (int i = 1; i <= us; i++) {
            sonuc *= taban;
        }
        System.out.println("Sonuç: " + sonuc);
    }
}
