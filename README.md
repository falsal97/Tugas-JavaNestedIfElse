# Tugas-JavaNestedIfElse
import java.util.Scanner;

public class main {
    private static String x;

    public static void main(String[] args) {
        System.out.println("Masukan Umur Anda ");
        Scanner input = new Scanner(System.in);
        int usia = input.nextInt();
        if (usia <= 12) {
            System.out.println("Kategori : Anak-anak");
            System.out.println("Rekomendasi : Buku Cerita Remaja");
        } else if (usia >= 18) {
            System.out.println("Kategori : Dewasa");
            System.out.println("Rekomendasi : Buku non-fiksi");
        } else {
            System.out.println("Kategori : Remaja");
            System.out.println("Rekomendasi : Buku Petualangan");
        }

    }
}
