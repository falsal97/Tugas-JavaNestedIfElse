# Tugas-JavaNestedIfElse
import java.util.Scanner;

public class Tugas {
    public static void main(String[] args) throws Exception {
        Scanner inputUsia = new Scanner(System.in);
        System.out.println("Berapa usia anda?");
        int usia = inputUsia.nextInt();
        if (usia <= 12) {
            System.out.println("Anak-anak"); 
            System.out.println("Buku Cerita");
        } else if (usia >= 13 && usia <= 17) {
            System.out.println("Remaja");
            System.out.println("Buku Petualangan");
        } else {
            System.out.println("Dewasa");
            System.out.println("Buku Non-Fiksi");
        }
    }
}
