# Hesap-Makinesi

         import java.util.Scanner;
     public class hesapMakinesi {
       public static void main(String[] args) {
        int n1,n2,select;

        Scanner inp = new Scanner(System.in);

        System.out.println("İlk sayıyı giriniz");
        n1= inp.nextInt();

        System.out.println("İkinci sayıyı giriniz");
        n2= inp.nextInt();

        System.out.println("1-Toplama\n2-Çıkarma\n3-Çarpma\n4- Bölme");
        System.out.println("Seçiminiz : ");
        select= inp.nextInt();


        switch (select){
            case 1 :
                System.out.println("Toplam :" +(n1+n2));
                break;
            case 2 :
                System.out.println("Çıkarma : "+(n1-n2));
                break;
            case 3 :
            System.out.println("Çarpma : " +(n1*n2));
              break;
            case 4 :
                if (n2==0) {
                    System.out.println("Bir sayı 0'a bölünmez! ");
                }else {
                    System.out.println("Bölme : " + (n1 / n2));
                }
            break;
            default:
                System.out.println("Hatalı giriş yaptınız");
          }







         }
     }
