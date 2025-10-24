import java.util.Scanner;

public class GanjilGenap {
public static void main(String[] args) {
Scanner input = new Scanner(System.in);

        System.out.print("Masukkan sebuah angka: ");
        int angka = input.nextInt();
jadi di program ini user di minta untuk memasukan sebuah angka
       


 if (angka % 2 == 0) {
            System.out.println(angka + " adalah bilangan genap.");
        } else {
            System.out.println(angka + " adalah bilangan ganjil.");
        }

        input.close();
    }

}

angka yang dimasukkan akan dimasukkan ke kondisi dimana apakah bilangan tersebut termasuk ganjil atau genab