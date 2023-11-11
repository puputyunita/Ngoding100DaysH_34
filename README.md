# Ngoding100DaysH_34
package ngoding100dayh_34;
//menentukan apkah angka tersbt ganjil atau genap dengan batas 
import java.util.Scanner;

public class Ngoding100dayH_34 {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("masukkan batas angka : ");
        int batas = input.nextInt();
        for (int i = 0; i <= batas; i++) {
            System.out.print("masukkan angka : ");
            int angka = input.nextInt();
            if (angka % 2 == 0 && angka != 0) {
                System.out.println("bilangan genap");
            } else if (angka % 2 != 0) {
                System.out.println("bilangan ganjil");
            } else {
                System.out.println("perulangan sudah mencapai batas");
            }
        }
    }

}
