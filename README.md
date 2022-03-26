# Dort-Bes-Kuvvet
Patika.dev > Java101 > Döngüler > Pratik3 - Girilen Sayıdan Küçük 4 ve 5’in Kuvvetlerini Bulan Program

Java döngüler ile girilen sayıya kadar olan 2'nin kuvvetlerini ekrana yazdıran programı yazıyoruz.

### Ödev

Java döngüler ile girilen sayıya kadar olan 4 ve 5'in kuvvetlerini ekrana yazdıran programı yazıyoruz. 

(soru 4 VEYA 5'in kuvvetlerini yazdıran program olarak çözülmüştür.)


      import java.util.*;

      public dort_bes_kuvvet {

        public static void main(String[] args) {

          Scanner sc = new Scanner(System.in);

          System.out.print("Please enter a number: ");
          int n = sc.nextInt();

          System.out.println("Multiples of 4: ");
          for (int i = 1; i < n; i*=4) {
            System.out.println(i);
          }

          System.out.println("Multiples of 5: ");
          for (int i = 1; i <= n; i *= 5) {
            System.out.println(i);
          }
        }
      }
